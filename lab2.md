# Lab Report 2 - Servers and Bugs

## Part 1
```
import java.io.IOException;
import java.net.URI;
import java.util.ArrayList;

class Handler implements URLHandler {
    ArrayList<String> messages = new ArrayList<String>(); 
    public String listStr(ArrayList<String> a){
        StringBuilder str = new StringBuilder();
        for (Object o : messages){
            str.append(o.toString());
            str.append("\n");
        }
        return str.toString();
    }

    public String handleRequest(URI url) {
        if (url.getPath().equals("/")) {
            return listStr(messages);
        } else {
            if (url.getPath().contains("/add-message")) {
                String[] parameters = url.getQuery().split("=");
                if (parameters[0].equals("s")) {
                    terms.add(parameters[1]);
                    return listStr(messages);
                }
            }
            return "404 Not Found!";
        }
    }
}
public class StringServer {
    public static void main(String[] args) throws IOException {
        if(args.length == 0){
            System.out.println("Missing port number! Try any number between 1024 to 49151");
            return;
        }
        int port = Integer.parseInt(args[0]);
        Server.start(port, new Handler());
    }
}
```
