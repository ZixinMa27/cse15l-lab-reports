# Lab Report 3
#### Zixin Ma 
#### Feb 13, 2023

## Researching Command - `grep`
Source: https://www.golinuxcloud.com/grep-command-in-linux/. Specifically, `-i` from 3. Perform case sensitive search using grep command; `-n` from 7. grep command to print line number; `-r` from 10. grep command to search in directories and sub-directories; `-l` from 11. grep command to print list of matching files only.

1. `$ grep -i pattern file_name`. Search for strings pattern case insensitively. 

- Input on files and its output:  
```
zixin@ZixindeMBP docsearch % grep -i "hong kong" ./written_2/travel_guides/berlitz1/*.txt
./written_2/travel_guides/berlitz1/HandRHongKong.txt:        Hong Kong has some of the most luxurious hotels in the
./written_2/travel_guides/berlitz1/HandRHongKong.txt:        limited room service, and a wide range of facilities. Hong Kong hotels
./written_2/travel_guides/berlitz1/HandRHongKong.txt:        arrangements, the Hong Kon Hotel Reservation Center at the
./written_2/travel_guides/berlitz1/HandRHongKong.txt:        indicate high-season rates in Hong Kong dollars, based on double
./written_2/travel_guides/berlitz1/HandRJamaica.txt:        Tel. 978-3476, 978-3479. Hong Kong chefs prepare traditional Chinese
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        In the popular mind, the history of Hong Kong, long the
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        uncover Hong Kong’s past, which stretches back thousands of years. You
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        While Hong Kong remained a relative backwater in early days,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        connections in India and the Middle East. By a.d. 900, the Hong Kong
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        got the island of Hong Kong. ” Her foreign secretary, Lord Palmerston,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        was not so amused; he dismissed Hong Kong as “a barren island with
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong Island formally became a British possession two
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        used in Hong Kong).
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Convention of Chuenpi, Britain was given the island of Hong Kong, and
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        losses. Hong Kong’s status as a British colony and a free port was
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        1907. Opium-smoking continued openly in Hong Kong until 1946; in
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        The first governor of Hong Kong, Sir Henry Pottinger,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Under his direction, Hong Kong began its march toward prosperity. It
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong leaped to the forefront as a base for trade. Both the
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        In the meantime, the opening of Hong Kong was the last blow
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong. No one ever discovered the identity or the motive of the
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        overthrew the Manchus, refugees flocked to the safety of Hong Kong.
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        assault on Hong Kong; Hong Kong’s minimal air force was destroyed on
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Territories and Kowloon, the defenders retreated to Hong Kong island,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Kong Chinese to the mainland. A number of Hong Kong’s monuments were
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        At the end of World War II, Hong Kong took stock of what
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong Comes Back
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        China’s civil war sent distressing echoes to Hong Kong.
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        refugees into Hong Kong multiplied, and by the time the People’s
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        the founders of Hong Kon’s now famous textile industry. In the late
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        1970s Hong Kong became the conduit for China’s goods, investment, and
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        always been scarce for Hong Kong’s Chinese. The problem became an
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        confirmed the transfer of the New Territories and all of Hong Kong to
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        China in 1997. For its part, China declared Hong Kong a “Special
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong’s existing laws and civil liberties would be upheld, refugees
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        effect prevented Hong Kong citizens from acquiring British citizenship,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        sympathy marches in Hong Kong, and further increased tension with
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        China. Some companies moved their headquarters out of Hong Kong.
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        the Hong Kong Chinese more political autonomy than they had done since
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        heartbeats in Hong Kong are the fluctuations of the Hang Seng Index,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        short, the status quo prevails. Everybody hopes Hong Kong will remain
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Hong Kong and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Hong Kong for at least a century. With its vibrant atmosphere and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        night-and-day activity it is an intoxicating place. Hong Kong is
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        the street. You’ll find Hong Kong easy to get around, the people
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        On 1 July, 1997 the British Crown Colony of Hong Kong
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        the People’s Republic of China. Today Hong Kong remains a capitalist
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Hong Kong will continue in this fashion for at least 50 years.
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Beijing’s announced policy of maintaining Hong Kong’s prosperity and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        stability makes sense. Hong Kong has long been China’s handiest window
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        the handover vanished from the front pages, the people of Hong Kong
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        replaced by the flag of China and the new Hong Kong flag with its
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Of Hong Kong’s population, 98 percent are Chinese. The
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        majority are Cantonese, born in Hong Kong, or from South China, but
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        to Hong Kong’s success. There are many stories of refugees who arrived
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        the horses. Hong Kong has two major racetracks as well as an intensive
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Sightseeing in Hong Kong starts at sea level with the
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Victoria Peak, Hong Kong’s highest point, or from skyscrapers and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        architecture are on Hong Kong Island. Across Victoria Harbor, connected
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        ponds. Hong Kong’s other, less developed islands, Lantau, Lamma, and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        now Hong Kong bristles with energy and ambition, and for the visitor,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Inflation has taken its toll in Hong Kong. While it’s no
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        some good buys to be had. Since Hong Kong is a duty-free port and
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Specialty goods and souvenirs, often handmade, come from Hong Kong and
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        elsewhere in China. Custom-made garments by skillful Hong Kong tailors
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        You’ll find that prices are about the same in Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong Tourist Association (HKTA), identified by a red junk logo.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Kowloon, especially along Nathan Road; Central on Hong Kong Island,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        City; Wing On, one of the oldest in Hong Kong; Marks and Spencer; and
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Malls. Hong Kong is full of giant malls. Harbour City, just
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        overruns. Hong Kong is no longer a factory outlet center since much of
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        skills. Hong Kong’s most famous and colorful market is the Temple
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Stanley Market is located on Hong Kong’s southern coast,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        the most famous antiques street in Hong Kong. Look for fine Chinese
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Cameras. Photo buffs know that Hong Kong is the place to
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Carpets and Rugs. Hong Kong is a mecca for Chinese
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        hand-knotted wool carpets and silk rugs. Hong Kong’s stores are usually
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        China (Porcelain). In Hong Kong you can have a plate, or
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong before anywhere else. Before you begin shopping, pick up
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Jewellery” published by the Hong Kong Tourist Authority to find a
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Leather Goods. Leather is not a great bargain in Hong Kong.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Musical, Audio, and Video Equipment. Hong Kong has a vast
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Ready-to-wear Clothes. Hong Kong’s shops carry almost every
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        in Hong Kong: more is spent on watches and clocks here than on cameras
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        help you choose a nightlife scene, pick up a copy of Hong Kong Tourist
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        wander through the maze of neon signs and take your pick. Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Kong Life is published by the Hong Kong Standard on Sunday, and the
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        A highlight of the arts calendar is the annual Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Arts takes place every other October, bringing to Hong Kong for two
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        There are more than 30 cinemas in Hong Kong, and the latest
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        The Hong Kong International Film Festival takes place in
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Performance Venues. The theaters in the Hong Kong Cultural
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        the Hong Kong Academy for the Performing Arts with two major theaters
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        for dance, drama, and concert performances; and the Hong Kong Arts
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        including the Queen Elizabeth Stadium, the Hong Kong Coliseum, and the
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Classical Music. The Hong Kong Chinese Orchestra performs
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        instruments are featured. The Hong Kong Philharmonic Orchestra was
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Dance. Hong Kong’s three professional dance companies — the
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong Ballet Company, the Hong Kong Dance Company, and the newer
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Theatre Company and the Hong Kong Repertory Theatre, perform in
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong by night can suit any taste — riotous, sedate,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Frin ge Club, 21 Lower Albert Road, Central, is Hong Kong’s best-known
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        71-77 Peking Road, is one of Hong Kong’s enduring Irish pubs.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Kwai Fong area, is popular with chuppies (Hong Kong yuppies) and has a
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Beaches. In subtropical Hong Kong you can swim from April
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        to early November. There are more than 40 beaches in Hong Kong that are
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        changing rooms, toilets, and snack stands. On Hong Kong Island, Repulse
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Golf. The Hong Kong Golf Club (Tel. 2812 7070) welcomes
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong residents and visitors take the express train to Guangzhou to
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong or 020-8350 7777). The 72-par course was designed by Dave
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        regions of Hong Kong.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        licensed by the Hong Kong authorities can run pleasure boats in local
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        waters. Contact the Hong Kong Yacht Club at Tel. 2832 2817 for
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        that improve concentration and balance at Garden Plaza, Hong Kong Park,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        June, and Hong Kong maintains two tracks — the older Happy Valley
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        course on Hong Kong Island and the striking Sha Tin track in the New
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Territories. The Hong Kon Tourist Association runs a “Come Horseracing
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Tour,” which includes entry to the Hong Kong Jockey Club visitors’ box
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Cricket. The Hong Kong International Cricket Series, held
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Children’s Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong has many attractions that appeal to children of
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        all ages. Hong Kong’s many beaches are especially fun for children.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Children love riding on Hong Kong’s antique trams. A ride on the Peak
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong’s state-of-the-art interactive museums will
./written_2/travel_guides/berlitz1/WhatToMalaysia.txt:        The discount shopping centers here rival those of Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        begin across Victoria Harbor on Hong Kong Island, where the city was
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Central
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        soaring skyline of Hong Kong Island draws nearer.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        On Connaught Road Central, you’ll find one of Hong Kong’s curiosities,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        wholesale food market ofHong Kong, and the Hang Seng building (private
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        few colonial buildings left in Hong Kong. So great is the pressure on
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        the available land that most of Hong Kong’s colonial architectural
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Bank of China Tower, not beloved by the people of Hong Kong — its
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        antennae. The rival Hong Kong and Shanghai Bank is by architect Norman
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        You can catch one of Hong Kong’s historic trams along Des
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        is Hong Kong’s oldest church. During World War II, the church was
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Park. The park’s 10.5 hectares (25 acres) of landscaped
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        House Museum of Tea Ware (see page 54). It’s in Hong Kong’s oldest
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Peak is still the most fashionable place to live in Hong Kong, but real
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        also souvenir stands, benches for a rest, and perhaps Hong Kong’s last
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        the Japanese during the occupation of Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        More Hong Kong Island Sights
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        The Western District is one of Hong Kong’s oldest
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong University’s campus is spread along Bonham Road.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        pharmacology and the history of medicine in Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        The Wan Chai waterfront is dominated by the Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        second only to Tsim Sha Tsui as Hong Kong’s place to shop. A prosperous
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Yacht Club has its headquarters. Across Gloucester Road,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Farther east is Hong Kon’s largest park, Victoria Park,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        is celebrated here and in all Hong Kong fishing communities.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        mosquitoes. It is home to Hong Kong’s first racetrack. Hong Kong’s
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        HK$75 children), which has become one of Hong Kong’s biggest
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Though much smaller thanHong Kong Island, Kowloon has
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Island. If you continue to the end of the promenade, you will
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Flanked by the clock tower is the imposing Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Cultural Centre. Hong Kong’s major venue for the performing arts, the
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Next door is the Hong Kong Space Museum and Theatre (open
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Museum of Art (see page 54) stands behind the Space Museum
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        is the collection of paintings and photographs of old Hong Kong. The
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        artifacts pertaining showcases 6,000 years of Hong Kong’s history and
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        tower. Its restored lobby is Hong Kong’s most elegant gathering place;
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Alongside the hotel runs busy Nathan Road, Hong Kong’s
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        governor of Hong Kong at the turn of the 19th century. At the time it
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong’s liveliest market scene is the Temple Street
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Bird Garden (open 8am–7pm). Birds are favorite pets in Hong Kong,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong’s New Territories begin at Boundary Street.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong’s highest peak at 957 m (3,140 ft). The highway continues
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        parallel to the coast. One-third of all Hong Kong’s beaches are to be
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        known as Hong Kong’s “window on China” — in the years of China’s
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Chinese University of Hong Kong is visible. Teaching here is conducted
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        of Hong Kong harbor that include a look at some of its 235 outlying
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Island you can escape to islands without cars or cares, where
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        colony, and covers nearly twice the area of Hong Kong Island. Chek Lap
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        monastery are the site of Hong Kong’s only tea plantation. Visitors are
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Some 10 km (6 miles) west of Hong Kong lies this small,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Cheung Chau becomes the center of Hong Kong life once a
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        back to watch the bananas grow. Hong Kong’s third largest island has a
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        4,000 years, and the island is known as “Hong Kong’s Stone Age Island.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        rise of Hong Kong, Macau became an isolated Portuguese outpost.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        little more like Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        the Shun Tak Centre, 200 Connaught Road, Central, in Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Entry procedures are similar to those in Hong Kong — most
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        currency, the pataca, is pegged to the Hong Kong dollar, and you can
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        use your Hong Kong currency freely in Macau.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        arrive from Hong Kong is the first surprise to greet visitors to
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        wildly popular with the Chinese of Hong Kong, and they make up nearly
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Like Hong Kong, Macau is a duty-free port. It is famous
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        There are many package tours to Guangzhou from Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Turbo Cat ferries leave the China Hong Kong City (CHKC) terminal twice
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        information). Hong Kong currency is widely accepted in Guangzhou, or
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Guangzhou, like Hong Kon, is primarily
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        the answer to Hong Kong. From a population of 20,000 it has grown into
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Because Shenzhen is much cheaper than Hong Kong, it is a
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        popular weekend destination for Hong Kong’s Chinese, who come to relax,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Cat ferry makes a one-hour trip (7am–7pm) from Hong Kong’s Macau Ferry
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        than Hong Kong. It is known for its inexpensive (but well-made)
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        knock-off designer goods. You can use your Hong Kong dollars here, so
./written_2/travel_guides/berlitz1/WhereToIndia.txt:        Singapore, the Peninsula inHong Kong, and the Imperial in Tokyo. You
./written_2/travel_guides/berlitz1/WhereToMalaysia.txt:        Majestic Station Hotel. The High Court and Hong Kong and Shanghai Bank
```
- Explanation: We search for pattern "hong kong" or "HONG KONG" case insensitively within ./written_2/travel_guides/berlitz1/ directory files. This is useful because we may sometimes forget ignore the importance of case, whether it is uppercase or lowercase letter. Using `-l`, we do not need to worry about the letter case.

- Input on directory and its output:
```
zixin@ZixindeMBP docsearch % grep -i "hong kong" ./written_2 
grep: ./written_2: Is a directory
```
- Explanation: We search for pattern "hong kong" or "HONG KONG" case insensitively within `./written_2` directory. But it is a dirctory, and contains no files, so we will not able to find any matches.

2. `$ grep -n pattern file_name` Search the line number of the pattern that is matched.

Input on file and its output:  
```
zixin@ZixindeMBP docsearch % grep --color -n "Hong Kong" ./written_2/travel_guides/berlitz1/*.txt
./written_2/travel_guides/berlitz1/HandRHongKong.txt:7:        Hong Kong has some of the most luxurious hotels in the
./written_2/travel_guides/berlitz1/HandRHongKong.txt:10:        limited room service, and a wide range of facilities. Hong Kong hotels
./written_2/travel_guides/berlitz1/HandRHongKong.txt:15:        arrangements, the Hong Kong Hotel Reservation Center at the
./written_2/travel_guides/berlitz1/HandRHongKong.txt:19:        indicate high-season rates in Hong Kong dollars, based on double
./written_2/travel_guides/berlitz1/HandRJamaica.txt:368:        Tel. 978-3476, 978-3479. Hong Kong chefs prepare traditional Chinese
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:7:        In the popular mind, the history of Hong Kong, long the
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:11:        uncover Hong Kong’s past, which stretches back thousands of years. You
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:18:        While Hong Kong remained a relative backwater in early days,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:20:        connections in India and the Middle East. By a.d. 900, the Hong Kong
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:44:        got the island of Hong Kong. ” Her foreign secretary, Lord Palmerston,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:45:        was not so amused; he dismissed Hong Kong as “a barren island with
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:47:        Hong Kong Island formally became a British possession two
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:61:        used in Hong Kong).
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:76:        Convention of Chuenpi, Britain was given the island of Hong Kong, and
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:86:        losses. Hong Kong’s status as a British colony and a free port was
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:91:        1907. Opium-smoking continued openly in Hong Kong until 1946; in
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:95:        The first governor ofHong Kong, Sir Henry Pottinger,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:97:        Under his direction, Hong Kong began its march toward prosperity. It
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:99:        Hong Kong leaped to the forefront as a base for trade. Both the
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:102:        In the meantime, the opening of Hong Kong was the last blow
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:118:        Hong Kong. No one ever discovered the identity or the motive of the
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:139:        overthrew the Manchus, refugees flocked to the safety of Hong Kong.
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:147:        assault on Hong Kong; Hong Kong’s minimal air force was destroyed on
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:149:        Territories and Kowloon, the defenders retreated to Hong Kong island,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:153:        Kong Chinese to the mainland. A number of Hong Kong’s monuments were
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:158:        At the end of World War II, Hong Kong took stock of what
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:161:        Hong Kong Comes Back
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:162:        China’s civil war sent distressing echoes to Hong Kong.
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:164:        refugees into Hong Kong multiplied, and by the time the People’s
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:169:        the founders of Hong Kong’s now famous textile industry. In the late
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:170:        1970s Hong Kong became the conduit for China’s goods, investment, and
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:174:        always been scarce for Hong Kong’s Chinese. The problem became an
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:190:        confirmed the transfer of the New Territories and all of Hong Kong to
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:191:        China in 1997. For its part, China declared Hong Kong a “Special
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:194:        Hong Kong’s existing laws and civil liberties would be upheld, refugees
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:196:        effect prevented Hong Kong citizens from acquiring British citizenship,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:200:        sympathy marches in Hong Kong, and further increased tension with
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:201:        China. Some companies moved their headquarters out of Hong Kong.
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:203:        the Hong Kong Chinese more political autonomy than they had done since
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:208:        heartbeats in Hong Kong are the fluctuations of the Hang Seng Index,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:210:        short, the status quo prevails. Everybody hopes Hong Kong will remain
./written_2/travel_guides/berlitz1/IntroHongKong.txt:6:        Hong Kong and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:9:        Hong Kong for at least a century. With its vibrant atmosphere and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:10:        night-and-day activity it is an intoxicating place. Hong Kong is
./written_2/travel_guides/berlitz1/IntroHongKong.txt:16:        the street. You’ll findHong Kong easy to get around, the people
./written_2/travel_guides/berlitz1/IntroHongKong.txt:19:        On 1 July, 1997 the British Crown Colony of Hong Kong
./written_2/travel_guides/berlitz1/IntroHongKong.txt:21:        the People’s Republic of China. Today Hong Kong remains a capitalist
./written_2/travel_guides/berlitz1/IntroHongKong.txt:23:        Hong Kong will continue in this fashion for at least 50 years.
./written_2/travel_guides/berlitz1/IntroHongKong.txt:24:        Beijing’s announced policy of maintaining Hong Kong’s prosperity and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:25:        stability makes sense. Hong Kong has long been China’s handiest window
./written_2/travel_guides/berlitz1/IntroHongKong.txt:29:        the handover vanished from the front pages, the people of Hong Kong
./written_2/travel_guides/berlitz1/IntroHongKong.txt:35:        replaced by the flag of China and the new Hong Kong flag with its
./written_2/travel_guides/berlitz1/IntroHongKong.txt:52:        Of Hong Kong’s population, 98 percent are Chinese. The
./written_2/travel_guides/berlitz1/IntroHongKong.txt:53:        majority are Cantonese, born in Hong Kong, or from South China, but
./written_2/travel_guides/berlitz1/IntroHongKong.txt:56:        to Hong Kong’s success. There are many stories of refugees who arrived
./written_2/travel_guides/berlitz1/IntroHongKong.txt:66:        the horses. Hong Kong has two major racetracks as well as an intensive
./written_2/travel_guides/berlitz1/IntroHongKong.txt:69:        Sightseeing in Hong Kon starts at sea level with the
./written_2/travel_guides/berlitz1/IntroHongKong.txt:72:        Victoria Peak, Hong Kon’s highest point, or from skyscrapers and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:76:        architecture are on Hong Kong Island. Across Victoria Harbor, connected
./written_2/travel_guides/berlitz1/IntroHongKong.txt:81:        ponds. Hong Kong’s other, less developed islands, Lantau, Lamma, and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:86:        now Hong Kong bristles with energy and ambition, and for the visitor,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:8:        Inflation has taken its toll in Hong Kong. While it’s no
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:10:        some good buys to be had. Since Hong Kong is a duty-free port and
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:14:        Specialty goods and souvenirs, often handmade, come from Hong Kong and
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:15:        elsewhere in China. Custom-made garments by skillful Hong Kong tailors
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:19:        You’ll find that prices are about the same in Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:47:        Hong Kong Tourist Association (HKTA), identified by a red junk logo.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:60:        Kowloon, especially along Nathan Road; Central on Hong Kong Island,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:65:        City; Wing On, one of the oldest in Hong Kong; Marks and Spencer; and
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:67:        Malls. Hong Kong is full of giant malls. Harbour City, just
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:74:        overruns. Hong Kong is no longer a factory outlet center since much of
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:78:        skills. Hong Kong’s most famous and colorful market is the Temple
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:82:        Stanley Market is located on Hong Kong’s southern coast,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:92:        the most famous antiques street in Hong Kong. Look for fine Chinese
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:107:        Cameras. Photo buffs know that Hong Kong is the place to
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:113:        Carpets and Rugs. Hong Kong is a mecca for Chinese
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:114:        hand-knotted wool carpets and silk rugs. Hong Kong’s stores are usually
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:118:        China (Porcelain). InHong Kong you can have a plate, or
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:130:        Hong Kong before anywhere else. Before you begin shopping, pick up
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:153:        Jewellery” published by the Hong Kong Tourist Authority to find a
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:158:        Leather Goods. Leather is not a great bargain in Hong Kong.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:163:        Musical, Audio, and Video Equipment. Hong Kong has a vast
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:169:        Ready-to-wear Clothes. Hong Kong’s shops carry almost every
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:189:        in Hong Kong: more is spent on watches and clocks here than on cameras
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:195:        help you choose a nightlife scene, pick up a copy of Hong Kong Tourist
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:197:        wander through the maze of neon signs and take your pick. Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:199:        Kong Life is published by the Hong Kong Standard on Sunday, and the
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:204:        A highlight of the arts calendar is the annual Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:209:        Arts takes place every other October, bringing to Hong Kong for two
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:212:        There are more than 30 cinemas in Hong Kong, and the latest
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:217:        The Hong Kong International Film Festival takes place in
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:221:        Performance Venues. The theaters in the Hong Kong Cultural
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:225:        the Hong Kong Academy for the Performing Arts with two major theaters
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:226:        for dance, drama, and concert performances; and the Hong Kong Arts
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:230:        including the Queen Elizabeth Stadium, the Hong Kong Coliseum, and the
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:233:        Classical Music. The Hong Kong Chinese Orchestra performs
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:235:        instruments are featured. The Hong Kong Philharmonic Orchestra was
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:246:        Dance. Hong Kong’s three professional dance companies — the
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:247:        Hong Kong Ballet Company, the Hong Kong Dance Company, and the newer
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:251:        Theatre Company and the Hong Kong Repertory Theatre, perform in
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:259:        Hong Kong by night can suit any taste — riotous, sedate,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:269:        Frin ge Club, 21 Lower Albert Road, Central, is Hong Kong’s best-known
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:276:        71-77 Peking Road, is one of Hong Kong’s enduring Irish pubs.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:286:        Kwai Fong area, is popular with chuppies (Hong Kong yuppies) and has a
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:301:        Beaches. In subtropical Hong Kong you can swim from April
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:302:        to early November. There are more than 40 beaches in Hong Kong that are
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:304:        changing rooms, toilets, and snack stands. On Hong Kong Island, Repulse
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:310:        Golf. The Hong Kong Golf Club (Tel. 2812 7070) welcomes
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:315:        Hong Kong residents and visitors take the express train to Guangzhou to
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:317:        Hong Kong or 020-8350 7777). The 72-par course was designed by Dave
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:327:        regions of Hong Kong.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:331:        licensed by the Hong Kong authorities can run pleasure boats in local
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:332:        waters. Contact the Hong Kong Yacht Club at Tel. 2832 2817 for
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:335:        that improve concentration and balance at Garden Plaza, Hong Kong Park,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:342:        June, and Hong Kong maintains two tracks — the older Happy Valley
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:343:        course on Hong Kong Island and the striking Sha Tin track in the New
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:344:        Territories. The Hong Kong Tourist Association runs a “Come Horseracing
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:345:        Tour,” which includes entry to the Hong Kong Jockey Club visitors’ box
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:347:        Cricket. The Hong Kon International Cricket Series, held
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:351:        Children’s Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:352:        Hong Kong has many attractions that appeal to children of
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:353:        all ages. Hong Kong’s many beaches are especially fun for children.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:354:        Children love riding on Hong Kong’s antique trams. A ride on the Peak
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:361:        Hong Kong’s state-of-the-art interactive museums will
./written_2/travel_guides/berlitz1/WhatToMalaysia.txt:140:        The discount shopping centers here rival those of Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:9:        begin across Victoria Harbor on Hong Kong Island, where the city was
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:12:        Hong Kong Central
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:21:        soaring skyline of Hong Kong Island draws nearer.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:30:        On Connaught Road Central, you’ll find one of Hong Kong’s curiosities,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:34:        wholesale food market of Hong Kong, and the Hang Seng building (private
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:40:        few colonial buildings left in Hong Kong. So great is the pressure on
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:41:        the available land that most of Hong Kong’s colonial architectural
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:46:        Bank of China Tower, not beloved by the people of Hong Kong — its
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:49:        antennae. The rival Hong Kong and Shanghai Bank is by architect Norman
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:54:        You can catch one of Hong Kong’s historic trams along Des
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:61:        is Hong Kong’s oldest church. During World War II, the church was
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:67:        Hong Kong Park. The park’s 10.5 hectares (25 acres) of landscaped
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:70:        House Museum of Tea Ware (see page 54). It’s in Hong Kong’s oldest
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:83:        Peak is still the most fashionable place to live in Hong Kong, but real
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:104:        also souvenir stands, benches for a rest, and perhaps Hong Kong’s last
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:109:        the Japanese during the occupation of Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:119:        More Hong Kong Island Sights
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:121:        The Western District is one of Hong Kong’s oldest
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:131:        Hong Kong University’s campus is spread along Bonham Road.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:164:        pharmacology and the history of medicine in Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:173:        The Wan Chai waterfront is dominated by the Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:188:        second only to Tsim Sha Tsui as Hong Kong’s place to shop. A prosperous
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:194:        Hong Kong Yacht Club has its headquarters. Across Gloucester Road,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:205:        Farther east is Hong Kong’s largest park, Victoria Park,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:211:        is celebrated here and in all Hong Kong fishing communities.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:214:        mosquitoes. It is home to Hong Kong’s first racetrack. Hong Kong’s
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:251:        HK$75 children), which has become one of Hong Kong’s biggest
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:277:        Though much smaller than Hong Kong Island, Kowloon has
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:290:        Hong Kong Island. If you continue to the end of the promenade, you will
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:293:        Flanked by the clock tower is the imposing Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:294:        Cultural Centre. Hong Kong’s major venue for the performing arts, the
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:300:        Next door is the Hong Kong Space Museum and Theatre (open
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:306:        Hong Kong Museum of Art (see page 54) stands behind the Space Museum
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:310:        is the collection of paintings and photographs of old Hong Kong. The
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:319:        artifacts pertaining showcases 6,000 years of Hong Kong’s history and
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:323:        tower. Its restored lobby is Hong Kong’s most elegant gathering place;
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:325:        Alongside the hotel runs busy Nathan Road, Hong Kong’s
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:328:        governor of Hong Kon at the turn of the 19th century. At the time it
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:341:        Hong Kong’s liveliest market scene is the Temple Street
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:355:        Bird Garden (open 8am–7pm). Birds are favorite pets in Hong Kong,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:367:        Hong Kong’s New Territories begin at Boundary Street.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:381:        Hong Kong’s highest peak at 957 m (3,140 ft). The highway continues
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:382:        parallel to the coast. One-third of all Hong Kong’s beaches are to be
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:390:        known as Hong Kong’s “window on China” — in the years of China’s
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:448:        Chinese University of Hong Kong is visible. Teaching here is conducted
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:479:        of Hong Kong harbor that include a look at some of its 235 outlying
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:483:        Hong Kong Island you can escape to islands without cars or cares, where
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:489:        colony, and covers nearly twice the area of Hong Kong Island. Chek Lap
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:512:        monastery are the site of Hong Kong’s only tea plantation. Visitors are
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:525:        Some 10 km (6 miles) west of Hong Kong lies this small,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:533:        Cheung Chau becomes the center of Hong Kong life once a
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:551:        back to watch the bananas grow. Hong Kong’s third largest island has a
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:555:        4,000 years, and the island is known as “Hong Kong’s Stone Age Island.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:592:        rise of Hong Kong, Macau became an isolated Portuguese outpost.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:604:        little more like Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:618:        the Shun Tak Centre, 200 Connaught Road, Central, in Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:620:        Entry procedures are similar to those in Hong Kong — most
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:622:        currency, the pataca, is pegged to the Hong Kong dollar, and you can
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:623:        use your Hong Kong currency freely in Macau.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:634:        arrive from Hong Kon is the first surprise to greet visitors to
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:744:        wildly popular with the Chinese of Hong Kong, and they make up nearly
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:763:        Like Hong Kong, Macau is a duty-free port. It is famous
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:847:        There are many package tours to Guangzhou from Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:852:        Turbo Cat ferries leave the China Hong Kong City (CHKC) terminal twice
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:856:        information). Hong Kong currency is widely accepted in Guangzhou, or
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:860:        Guangzhou, like Hong Kong, is primarily
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:951:        the answer to Hong Kong. From a population of 20,000 it has grown into
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:954:        Because Shenzhen is much cheaper than Hong Kong, it is a
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:955:        popular weekend destination for Hong Kong’s Chinese, who come to relax,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:964:        Cat ferry makes a one-hour trip (7am–7pm) from Hong Kong’s Macau Ferry
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:968:        than Hong Kong. It is known for its inexpensive (but well-made)
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:969:        knock-off designer goods. You can use your Hong Kong dollars here, so
./written_2/travel_guides/berlitz1/WhereToIndia.txt:1228:        Singapore, the Peninsula in Hong Kong, and the Imperial in Tokyo. You
./written_2/travel_guides/berlitz1/WhereToMalaysia.txt:531:        Majestic Station Hotel. The High Court and Hong Kong and Shanghai Bank
```
- Explanation: We search for pattern "Hong Kong" case sensitively within ./written_2/travel_guides/berlitz1/ directory files and display its line appear within the file. This is useful because we can easily locate the character, especially more convenient when searching large files.

Input on directory and its output:
```
zixin@ZixindeMBP docsearch % grep -n "Hong Kong" ./written_2            
grep: ./written_2: Is a directory
```

- Explanation: We search for pattern "Hong Kong" case sensitively within `./written_2` directory. But it is a dirctory, and contains no files, so we will not able to find any matches.


3. `$ grep -l pattern path` Search file names only that contain the matching patterns.
Input on files and its output:
```
zixin@ZixindeMBP docsearch % grep -l "Hong Kong" ./written_2/travel_guides/berlitz1/*.txt
./written_2/travel_guides/berlitz1/HandRHongKong.txt
./written_2/travel_guides/berlitz1/HandRJamaica.txt
./written_2/travel_guides/berlitz1/HistoryHongKong.txt
./written_2/travel_guides/berlitz1/IntroHongKong.txt
./written_2/travel_guides/berlitz1/WhatToHongKong.txt
./written_2/travel_guides/berlitz1/WhatToMalaysia.txt
./written_2/travel_guides/berlitz1/WhereToHongKong.txt
./written_2/travel_guides/berlitz1/WhereToIndia.txt
./written_2/travel_guides/berlitz1/WhereToMalaysia.txt
```
- Explanation: We search for filenames that contain pattern "Hong Kong" case sensitively within `./written_2` directory. But it is a dirctory, and contains no files, so we will not able to find any matches.

Input on directory and its output:
```
docsearch % grep -l "Hong Kong" ./written_2
grep: ./written_2: Is a directory
```
- Explanation: We search for filename that contain pattern "Hong Kong" case sensitively within ./written_2/travel_guides/berlitz1/ directory files. This is useful when I only want to find the filename instead of the content of the file.

4. `$ grep -r pattern path`. Searches the matches in all files in the directory passed in and including its sub-directories

Input on file and its output:
```
zixin@ZixindeMBP docsearch % grep -r "Hong Kong" ./written_2/travel_guides/berlitz1/*.txt   
./written_2/travel_guides/berlitz1/HandRHongKong.txt:        Hong Kong has some of the most luxurious hotels in the
./written_2/travel_guides/berlitz1/HandRHongKong.txt:        limited room service, and a wide range of facilities. Hong Kong hotels
./written_2/travel_guides/berlitz1/HandRHongKong.txt:        arrangements, the Hong Kong Hotel Reservation Center at the
./written_2/travel_guides/berlitz1/HandRHongKong.txt:        indicate high-season rates in Hong Kong dollars, based on double
./written_2/travel_guides/berlitz1/HandRJamaica.txt:        Tel. 978-3476, 978-3479. Hong Kong chefs prepare traditional Chinese
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        In the popular mind, the history of Hong Kong, long the
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        uncover Hong Kong’s past, which stretches back thousands of years. You
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        While Hong Kong remained a relative backwater in early days,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        connections in India and the Middle East. By a.d. 900, the Hong Kong
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        got the island of Hong Kong. ” Her foreign secretary, Lord Palmerston,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        was not so amused; he dismissed Hong Kong as “a barren island with
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong Island formally became a British possession two
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        used in Hong Kong).
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Convention of Chuenpi, Britain was given the island of Hong Kong, and
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        losses. Hong Kong’s status as a British colony and a free port was
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        1907. Opium-smoking continued openly in Hong Kong until 1946; in
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        The first governor of Hong Kong, Sir Henry Pottinger,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Under his direction, Hong Kong began its march toward prosperity. It
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong leaped to the forefront as a base for trade. Both the
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        In the meantime, the opening of Hong Kong was the last blow
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong. No one ever discovered the identity or the motive of the
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        overthrew the Manchus, refugees flocked to the safety of Hong Kong.
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        assault on Hong Kong; Hong Kong’s minimal air force was destroyed on
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Territories and Kowloon, the defenders retreated to Hong Kong island,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Kong Chinese to the mainland. A number of Hong Kong’s monuments were
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        At the end of World War II, Hong Kong took stock of what
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong Comes Back
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        China’s civil war sent distressing echoes to Hong Kong.
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        refugees into Hong Kong multiplied, and by the time the People’s
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        the founders of Hong Kong’s now famous textile industry. In the late
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        1970s Hong Kong became the conduit for China’s goods, investment, and
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        always been scarce for Hong Kong’s Chinese. The problem became an
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        confirmed the transfer of the New Territories and all of Hong Kong to
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        China in 1997. For its part, China declared Hong Kong a “Special
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong’s existing laws and civil liberties would be upheld, refugees
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        effect prevented Hong Kong citizens from acquiring British citizenship,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        sympathy marches in Hong Kong, and further increased tension with
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        China. Some companies moved their headquarters out of Hong Kong.
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        the Hong Kong Chinese more political autonomy than they had done since
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        heartbeats in Hong Kong are the fluctuations of the Hang Seng Index,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        short, the status quo prevails. Everybody hopes Hong Kong will remain
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Hong Kong and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Hong Kong for at least a century. With its vibrant atmosphere and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        night-and-day activity it is an intoxicating place. Hong Kong is
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        the street. You’ll find Hong Kong easy to get around, the people
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        On 1 July, 1997 the British Crown Colony of Hong Kong
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        the People’s Republic of China. Today Hong Kong remains a capitalist
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Hong Kong will continue in this fashion for at least 50 years.
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Beijing’s announced policy of maintaining Hong Kong’s prosperity and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        stability makes sense. Hong Kong has long been China’s handiest window
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        the handover vanished from the front pages, the people of Hong Kong
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        replaced by the flag of China and the new Hong Kong flag with its
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Of Hong Kong’s population, 98 percent are Chinese. The
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        majority are Cantonese, born in Hong Kong, or from South China, but
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        to Hong Kong’s success. There are many stories of refugees who arrived
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        the horses. Hong Kong has two major racetracks as well as an intensive
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Sightseeing in Hong Kong starts at sea level with the
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Victoria Peak, Hong Kong’s highest point, or from skyscrapers and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        architecture are on Hong Kong Island. Across Victoria Harbor, connected
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        ponds. Hong Kong’s other, less developed islands, Lantau, Lamma, and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        now Hong Kong bristles with energy and ambition, and for the visitor,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Inflation has taken its toll in Hong Kong. While it’s no
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        some good buys to be had. Since Hong Kong is a duty-free port and
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Specialty goods and souvenirs, often handmade, come from Hong Kong and
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        elsewhere in China. Custom-made garments by skillful Hong Kong tailors
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        You’ll find that prices are about the same in Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong Tourist Association (HKTA), identified by a red junk logo.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Kowloon, especially along Nathan Road; Central on Hong Kong Island,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        City; Wing On, one of the oldest in Hong Kong; Marks and Spencer; and
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Malls. Hong Kong is full of giant malls. Harbour City, just
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        overruns. Hong Kong is no longer a factory outlet center since much of
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        skills. Hong Kong’s most famous and colorful market is the Temple
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Stanley Market is located on Hong Kong’s southern coast,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        the most famous antiques street in Hong Kong. Look for fine Chinese
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Cameras. Photo buffs know that Hong Kong is the place to
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Carpets and Rugs. Hong Kong is a mecca for Chinese
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        hand-knotted wool carpets and silk rugs. Hong Kong’s stores are usually
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        China (Porcelain). In Hong Kong you can have a plate, or
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong before anywhere else. Before you begin shopping, pick up
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Jewellery” published by the Hong Kong Tourist Authority to find a
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Leather Goods. Leather is not a great bargain in Hong Kong.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Musical, Audio, and Video Equipment. Hong Kong has a vast
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Ready-to-wear Clothes. Hong Kong’s shops carry almost every
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        in Hong Kong: more is spent on watches and clocks here than on cameras
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        help you choose a nightlife scene, pick up a copy of Hong Kong Tourist
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        wander through the maze of neon signs and take your pick. Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Kong Life is published by the Hong Kong Standard on Sunday, and the
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        A highlight of the arts calendar is the annual Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Arts takes place every other October, bringing to Hong Kong for two
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        There are more than 30 cinemas in Hong Kong, and the latest
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        The Hong Kong International Film Festival takes place in
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Performance Venues. The theaters in the Hong Kong Cultural
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        the Hong Kong Academy for the Performing Arts with two major theaters
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        for dance, drama, and concert performances; and the Hong Kong Arts
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        including the Queen Elizabeth Stadium, the Hong Kong Coliseum, and the
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Classical Music. The Hong Kong Chinese Orchestra performs
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        instruments are featured. The Hong Kong Philharmonic Orchestra was
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Dance. Hong Kong’s three professional dance companies — the
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong Ballet Company, the Hong Kong Dance Company, and the newer
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Theatre Company and the Hong Kong Repertory Theatre, perform in
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong by night can suit any taste — riotous, sedate,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Frin ge Club, 21 Lower Albert Road, Central, is Hong Kong’s best-known
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        71-77 Peking Road, is one of Hong Kong’s enduring Irish pubs.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Kwai Fong area, is popular with chuppies (Hong Kong yuppies) and has a
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Beaches. In subtropical Hong Kong you can swim from April
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        to early November. There are more than 40 beaches in Hong Kong that are
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        changing rooms, toilets, and snack stands. On Hong Kong Island, Repulse
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Golf. The Hong Kong Golf Club (Tel. 2812 7070) welcomes
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong residents and visitors take the express train to Guangzhou to
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong or 020-8350 7777). The 72-par course was designed by Dave
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        regions of Hong Kong.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        licensed by the Hong Kong authorities can run pleasure boats in local
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        waters. Contact the Hong Kong Yacht Club at Tel. 2832 2817 for
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        that improve concentration and balance at Garden Plaza, Hong Kong Park,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        June, and Hong Kong maintains two tracks — the older Happy Valley
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        course on Hong Kong Island and the striking Sha Tin track in the New
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Territories. The Hong Kong Tourist Association runs a “Come Horseracing
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Tour,” which includes entry to the Hong Kong Jockey Club visitors’ box
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Cricket. The Hong Kong International Cricket Series, held
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Children’s Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong has many attractions that appeal to children of
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        all ages. Hong Kong’s many beaches are especially fun for children.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Children love riding on Hong Kong’s antique trams. A ride on the Peak
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong’s state-of-the-art interactive museums will
./written_2/travel_guides/berlitz1/WhatToMalaysia.txt:        The discount shopping centers here rival those of Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        begin across Victoria Harbor on Hong Kong Island, where the city was
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Central
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        soaring skyline of Hong Kong Island draws nearer.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        On Connaught Road Central, you’ll find one of Hong Kong’s curiosities,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        wholesale food market of Hong Kong, and the Hang Seng building (private
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        few colonial buildings left in Hong Kong. So great is the pressure on
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        the available land that most of Hong Kong’s colonial architectural
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Bank of China Tower, not beloved by the people of Hong Kong — its
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        antennae. The rival Hong Kong and Shanghai Bank is by architect Norman
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        You can catch one of Hong Kong’s historic trams along Des
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        is Hong Kong’s oldest church. During World War II, the church was
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Park. The park’s 10.5 hectares (25 acres) of landscaped
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        House Museum of Tea Ware (see page 54). It’s in Hong Kong’s oldest
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Peak is still the most fashionable place to live in Hong Kong, but real
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        also souvenir stands, benches for a rest, and perhaps Hong Kong’s last
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        the Japanese during the occupation of Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        More Hong Kong Island Sights
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        The Western District is one of Hong Kong’s oldest
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong University’s campus is spread along Bonham Road.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        pharmacology and the history of medicine in Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        The Wan Chai waterfront is dominated by the Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        second only to Tsim Sha Tsui as Hong Kong’s place to shop. A prosperous
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Yacht Club has its headquarters. Across Gloucester Road,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Farther east is Hong Kong’s largest park, Victoria Park,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        is celebrated here and in all Hong Kong fishing communities.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        mosquitoes. It is home to Hong Kong’s first racetrack. Hong Kong’s
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        HK$75 children), which has become one of Hong Kong’s biggest
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Though much smaller than Hong Kong Island, Kowloon has
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Island. If you continue to the end of the promenade, you will
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Flanked by the clock tower is the imposing Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Cultural Centre. Hong Kong’s major venue for the performing arts, the
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Next door is the Hong Kong Space Museum and Theatre (open
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Museum of Art (see page 54) stands behind the Space Museum
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        is the collection of paintings and photographs of old Hong Kong. The
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        artifacts pertaining showcases 6,000 years of Hong Kong’s history and
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        tower. Its restored lobby is Hong Kong’s most elegant gathering place;
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Alongside the hotel runs busy Nathan Road, Hong Kong’s
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        governor of Hong Kong at the turn of the 19th century. At the time it
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong’s liveliest market scene is the Temple Street
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Bird Garden (open 8am–7pm). Birds are favorite pets in Hong Kong,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong’s New Territories begin at Boundary Street.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong’s highest peak at 957 m (3,140 ft). The highway continues
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        parallel to the coast. One-third of all Hong Kong’s beaches are to be
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        known as Hong Kong’s “window on China” — in the years of China’s
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Chinese University of Hong Kong is visible. Teaching here is conducted
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        of Hong Kong harbor that include a look at some of its 235 outlying
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Island you can escape to islands without cars or cares, where
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        colony, and covers nearly twice the area of Hong Kong Island. Chek Lap
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        monastery are the site of Hong Kong’s only tea plantation. Visitors are
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Some 10 km (6 miles) west of Hong Kong lies this small,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Cheung Chau becomes the center of Hong Kong life once a
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        back to watch the bananas grow. Hong Kong’s third largest island has a
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        4,000 years, and the island is known as “Hong Kong’s Stone Age Island.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        rise of Hong Kong, Macau became an isolated Portuguese outpost.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        little more like Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        the Shun Tak Centre, 200 Connaught Road, Central, in Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Entry procedures are similar to those in Hong Kong — most
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        currency, the pataca, is pegged to the Hong Kong dollar, and you can
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        use your Hong Kong currency freely in Macau.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        arrive from Hong Kong is the first surprise to greet visitors to
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        wildly popular with the Chinese of Hong Kong, and they make up nearly
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Like Hong Kong, Macau is a duty-free port. It is famous
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        There are many package tours to Guangzhou from Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Turbo Cat ferries leave the China Hong Kong City (CHKC) terminal twice
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        information). Hong Kong currency is widely accepted in Guangzhou, or
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Guangzhou, like Hong Kong, is primarily
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        the answer to Hong Kong. From a population of 20,000 it has grown into
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Because Shenzhen is much cheaper than Hong Kong, it is a
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        popular weekend destination for Hong Kong’s Chinese, who come to relax,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Cat ferry makes a one-hour trip (7am–7pm) from Hong Kong’s Macau Ferry
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        than Hong Kong. It is known for its inexpensive (but well-made)
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        knock-off designer goods. You can use your Hong Kong dollars here, so
./written_2/travel_guides/berlitz1/WhereToIndia.txt:        Singapore, the Peninsula in Hong Kong, and the Imperial in Tokyo. You
./written_2/travel_guides/berlitz1/WhereToMalaysia.txt:        Majestic Station Hotel. The High Court and Hong Kong and Shanghai Bank
```
- Explanation:
We search for pattern "Hong kong" case sensitively within ./written_2/travel_guides/berlitz1/ directory files and including its sub-directories. Since there is no more subdirectories, in this case, it is same as `grep "Hong Kong" ./written_2/travel_guides/berlitz1/*.txt`


Input on dirctory and its output:
```
zixin@ZixindeMBP docsearch % grep -r "Hong Kong" ./written_2
./written_2/non-fiction/OUP/Abernathy/ch1.txt:But hourly compensation levels have increasingly hurt U.S. apparel-makers, if performance is principally determined on a price/cost basis. For example, because of wage differentials between the countries, U.S. apparel-makers would need to be 2.5 times more productive than firms in Hong Kong to be “competitive.” As a result, U.S. shirt manufacturers lost enormous market share to offshore producers. And employment in men’s and boys’ shirts between 1972 and 1996 declined an average of 3 percent a year.22
./written_2/non-fiction/OUP/Abernathy/ch1.txt:Trade data already suggest a major restructuring in the sources of U.S. apparel imports. The surge in apparel imports in the 1980s came from low-wage countries, primarily the Asian “Big Four”—the People’s Republic of China, Hong Kong, Taiwan, and Korea. This group of nations provided 39 percent of all apparel imports in 1964 and 51 percent of all apparel imports by 1988 (measured in square-meter equivalents, a measure of quantity). But by 1996, the Big Four’s share of imports had fallen to 26 percent. Their U.S. share has been increasingly displaced by those of Mexico and Caribbean nations.35 Although these shifts in part reflect changes in U.S. trade policy, such as the North American Free Trade Agreement (NAFTA), they fundamentally arise from new sourcing patterns attributable to channel integration and the consequent need for apparel items that can be delivered in a shorter time to the U.S. market.
./written_2/non-fiction/OUP/Abernathy/ch15.txt:The general analysis of the consequences of trade and immigration in the textile and apparel industries clearly requires a much more focused application to detailed sectors to provide reliable conclusions. Moreover, and as this volume indicates, the offsetting influences of lean retailing and short-cycle production in comparison with low foreign labor rates must be evaluated by product demand variability, rather than simply making generalizations about aggregate trade and immigration. For instance, the information-integrated channels in retail-apparel-textile are having some of their most significant impact on sourcing among suppliers, domestic and foreign. The low labor costs for sewing and short time to market from Mexico and the Caribbean countries, and the provisions of the Harmonized Tariff Schedule (formerly Section 807 and 807a, or currently 9802.00.80) that establish duties only on the value added to U.S.-produced materials sent out for assembly, all favor sourcing of apparel from south of the U.S. border rather than Asia. According to the U.S. International Trade Commission, “U.S. imports of textiles and apparel from China and two of the traditional Big Three Asian suppliers—Hong Kong and Korea—continued to decline in 1996, when these countries together with Taiwan, accounted for 23.4 percent of total sector trade, compared with 38.5 percent in 1991.”6
./written_2/travel_guides/berlitz1/HandRJamaica.txt:        Tel. 978-3476, 978-3479. Hong Kong chefs prepare traditional Chinese
./written_2/travel_guides/berlitz1/HandRHongKong.txt:        Hong Kong has some of the most luxurious hotels in the
./written_2/travel_guides/berlitz1/HandRHongKong.txt:        limited room service, and a wide range of facilities. Hong Kong hotels
./written_2/travel_guides/berlitz1/HandRHongKong.txt:        arrangements, the Hong Kong Hotel Reservation Center at the
./written_2/travel_guides/berlitz1/HandRHongKong.txt:        indicate high-season rates in Hong Kong dollars, based on double
./written_2/travel_guides/berlitz1/WhereToIndia.txt:        Singapore, the Peninsula in Hong Kong, and the Imperial in Tokyo. You
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        In the popular mind, the history of Hong Kong, long the
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        uncover Hong Kong’s past, which stretches back thousands of years. You
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        While Hong Kong remained a relative backwater in early days,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        connections in India and the Middle East. By a.d. 900, the Hong Kong
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        got the island of Hong Kong. ” Her foreign secretary, Lord Palmerston,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        was not so amused; he dismissed Hong Kong as “a barren island with
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong Island formally became a British possession two
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        used in Hong Kong).
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Convention of Chuenpi, Britain was given the island of Hong Kong, and
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        losses. Hong Kong’s status as a British colony and a free port was
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        1907. Opium-smoking continued openly in Hong Kong until 1946; in
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        The first governor of Hong Kong, Sir Henry Pottinger,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Under his direction, Hong Kong began its march toward prosperity. It
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong leaped to the forefront as a base for trade. Both the
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        In the meantime, the opening of Hong Kong was the last blow
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong. No one ever discovered the identity or the motive of the
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        overthrew the Manchus, refugees flocked to the safety of Hong Kong.
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        assault on Hong Kong; Hong Kong’s minimal air force was destroyed on
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Territories and Kowloon, the defenders retreated to Hong Kong island,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Kong Chinese to the mainland. A number of Hong Kong’s monuments were
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        At the end of World War II, Hong Kong took stock of what
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong Comes Back
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        China’s civil war sent distressing echoes to Hong Kong.
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        refugees into Hong Kong multiplied, and by the time the People’s
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        the founders of Hong Kong’s now famous textile industry. In the late
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        1970s Hong Kong became the conduit for China’s goods, investment, and
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        always been scarce for Hong Kong’s Chinese. The problem became an
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        confirmed the transfer of the New Territories and all of Hong Kong to
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        China in 1997. For its part, China declared Hong Kong a “Special
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        Hong Kong’s existing laws and civil liberties would be upheld, refugees
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        effect prevented Hong Kong citizens from acquiring British citizenship,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        sympathy marches in Hong Kong, and further increased tension with
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        China. Some companies moved their headquarters out of Hong Kong.
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        the Hong Kong Chinese more political autonomy than they had done since
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        heartbeats in Hong Kong are the fluctuations of the Hang Seng Index,
./written_2/travel_guides/berlitz1/HistoryHongKong.txt:        short, the status quo prevails. Everybody hopes Hong Kong will remain
./written_2/travel_guides/berlitz1/WhereToMalaysia.txt:        Majestic Station Hotel. The High Court and Hong Kong and Shanghai Bank
./written_2/travel_guides/berlitz1/WhatToMalaysia.txt:        The discount shopping centers here rival those of Hong Kong
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Hong Kong and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Hong Kong for at least a century. With its vibrant atmosphere and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        night-and-day activity it is an intoxicating place. Hong Kong is
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        the street. You’ll find Hong Kong easy to get around, the people
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        On 1 July, 1997 the British Crown Colony of Hong Kong
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        the People’s Republic of China. Today Hong Kong remains a capitalist
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Hong Kong will continue in this fashion for at least 50 years.
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Beijing’s announced policy of maintaining Hong Kong’s prosperity and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        stability makes sense. Hong Kong has long been China’s handiest window
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        the handover vanished from the front pages, the people of Hong Kong
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        replaced by the flag of China and the new Hong Kong flag with its
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Of Hong Kong’s population, 98 percent are Chinese. The
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        majority are Cantonese, born in Hong Kong, or from South China, but
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        to Hong Kong’s success. There are many stories of refugees who arrived
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        the horses. Hong Kong has two major racetracks as well as an intensive
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Sightseeing in Hong Kong starts at sea level with the
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        Victoria Peak, Hong Kong’s highest point, or from skyscrapers and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        architecture are on Hong Kong Island. Across Victoria Harbor, connected
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        ponds. Hong Kong’s other, less developed islands, Lantau, Lamma, and
./written_2/travel_guides/berlitz1/IntroHongKong.txt:        now Hong Kong bristles with energy and ambition, and for the visitor,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Inflation has taken its toll in Hong Kong. While it’s no
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        some good buys to be had. Since Hong Kong is a duty-free port and
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Specialty goods and souvenirs, often handmade, come from Hong Kong and
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        elsewhere in China. Custom-made garments by skillful Hong Kong tailors
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        You’ll find that prices are about the same in Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong Tourist Association (HKTA), identified by a red junk logo.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Kowloon, especially along Nathan Road; Central on Hong Kong Island,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        City; Wing On, one of the oldest in Hong Kong; Marks and Spencer; and
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Malls. Hong Kong is full of giant malls. Harbour City, just
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        overruns. Hong Kong is no longer a factory outlet center since much of
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        skills. Hong Kong’s most famous and colorful market is the Temple
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Stanley Market is located on Hong Kong’s southern coast,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        the most famous antiques street in Hong Kong. Look for fine Chinese
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Cameras. Photo buffs know that Hong Kong is the place to
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Carpets and Rugs. Hong Kong is a mecca for Chinese
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        hand-knotted wool carpets and silk rugs. Hong Kong’s stores are usually
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        China (Porcelain). In Hong Kong you can have a plate, or
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong before anywhere else. Before you begin shopping, pick up
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Jewellery” published by the Hong Kong Tourist Authority to find a
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Leather Goods. Leather is not a great bargain in Hong Kong.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Musical, Audio, and Video Equipment. Hong Kong has a vast
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Ready-to-wear Clothes. Hong Kong’s shops carry almost every
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        in Hong Kong: more is spent on watches and clocks here than on cameras
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        help you choose a nightlife scene, pick up a copy of Hong Kong Tourist
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        wander through the maze of neon signs and take your pick. Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Kong Life is published by the Hong Kong Standard on Sunday, and the
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        A highlight of the arts calendar is the annual Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Arts takes place every other October, bringing to Hong Kong for two
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        There are more than 30 cinemas in Hong Kong, and the latest
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        The Hong Kong International Film Festival takes place in
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Performance Venues. The theaters in the Hong Kong Cultural
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        the Hong Kong Academy for the Performing Arts with two major theaters
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        for dance, drama, and concert performances; and the Hong Kong Arts
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        including the Queen Elizabeth Stadium, the Hong Kong Coliseum, and the
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Classical Music. The Hong Kong Chinese Orchestra performs
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        instruments are featured. The Hong Kong Philharmonic Orchestra was
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Dance. Hong Kong’s three professional dance companies — the
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong Ballet Company, the Hong Kong Dance Company, and the newer
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Theatre Company and the Hong Kong Repertory Theatre, perform in
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong by night can suit any taste — riotous, sedate,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Frin ge Club, 21 Lower Albert Road, Central, is Hong Kong’s best-known
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        71-77 Peking Road, is one of Hong Kong’s enduring Irish pubs.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Kwai Fong area, is popular with chuppies (Hong Kong yuppies) and has a
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Beaches. In subtropical Hong Kong you can swim from April
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        to early November. There are more than 40 beaches in Hong Kong that are
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        changing rooms, toilets, and snack stands. On Hong Kong Island, Repulse
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Golf. The Hong Kong Golf Club (Tel. 2812 7070) welcomes
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong residents and visitors take the express train to Guangzhou to
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong or 020-8350 7777). The 72-par course was designed by Dave
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        regions of Hong Kong.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        licensed by the Hong Kong authorities can run pleasure boats in local
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        waters. Contact the Hong Kong Yacht Club at Tel. 2832 2817 for
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        that improve concentration and balance at Garden Plaza, Hong Kong Park,
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        June, and Hong Kong maintains two tracks — the older Happy Valley
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        course on Hong Kong Island and the striking Sha Tin track in the New
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Territories. The Hong Kong Tourist Association runs a “Come Horseracing
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Tour,” which includes entry to the Hong Kong Jockey Club visitors’ box
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Cricket. The Hong Kong International Cricket Series, held
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Children’s Hong Kong
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong has many attractions that appeal to children of
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        all ages. Hong Kong’s many beaches are especially fun for children.
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Children love riding on Hong Kong’s antique trams. A ride on the Peak
./written_2/travel_guides/berlitz1/WhatToHongKong.txt:        Hong Kong’s state-of-the-art interactive museums will
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        begin across Victoria Harbor on Hong Kong Island, where the city was
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Central
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        soaring skyline of Hong Kong Island draws nearer.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        On Connaught Road Central, you’ll find one of Hong Kong’s curiosities,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        wholesale food market of Hong Kong, and the Hang Seng building (private
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        few colonial buildings left in Hong Kong. So great is the pressure on
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        the available land that most of Hong Kong’s colonial architectural
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Bank of China Tower, not beloved by the people of Hong Kong — its
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        antennae. The rival Hong Kong and Shanghai Bank is by architect Norman
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        You can catch one of Hong Kong’s historic trams along Des
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        is Hong Kong’s oldest church. During World War II, the church was
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Park. The park’s 10.5 hectares (25 acres) of landscaped
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        House Museum of Tea Ware (see page 54). It’s in Hong Kong’s oldest
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Peak is still the most fashionable place to live in Hong Kong, but real
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        also souvenir stands, benches for a rest, and perhaps Hong Kong’s last
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        the Japanese during the occupation of Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        More Hong Kong Island Sights
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        The Western District is one of Hong Kong’s oldest
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong University’s campus is spread along Bonham Road.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        pharmacology and the history of medicine in Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        The Wan Chai waterfront is dominated by the Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        second only to Tsim Sha Tsui as Hong Kong’s place to shop. A prosperous
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Yacht Club has its headquarters. Across Gloucester Road,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Farther east is Hong Kong’s largest park, Victoria Park,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        is celebrated here and in all Hong Kong fishing communities.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        mosquitoes. It is home to Hong Kong’s first racetrack. Hong Kong’s
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        HK$75 children), which has become one of Hong Kong’s biggest
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Though much smaller than Hong Kong Island, Kowloon has
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Island. If you continue to the end of the promenade, you will
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Flanked by the clock tower is the imposing Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Cultural Centre. Hong Kong’s major venue for the performing arts, the
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Next door is the Hong Kong Space Museum and Theatre (open
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Museum of Art (see page 54) stands behind the Space Museum
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        is the collection of paintings and photographs of old Hong Kong. The
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        artifacts pertaining showcases 6,000 years of Hong Kong’s history and
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        tower. Its restored lobby is Hong Kong’s most elegant gathering place;
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Alongside the hotel runs busy Nathan Road, Hong Kong’s
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        governor of Hong Kong at the turn of the 19th century. At the time it
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong’s liveliest market scene is the Temple Street
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Bird Garden (open 8am–7pm). Birds are favorite pets in Hong Kong,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong’s New Territories begin at Boundary Street.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong’s highest peak at 957 m (3,140 ft). The highway continues
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        parallel to the coast. One-third of all Hong Kong’s beaches are to be
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        known as Hong Kong’s “window on China” — in the years of China’s
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Chinese University of Hong Kong is visible. Teaching here is conducted
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        of Hong Kong harbor that include a look at some of its 235 outlying
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Hong Kong Island you can escape to islands without cars or cares, where
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        colony, and covers nearly twice the area of Hong Kong Island. Chek Lap
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        monastery are the site of Hong Kong’s only tea plantation. Visitors are
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Some 10 km (6 miles) west of Hong Kong lies this small,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Cheung Chau becomes the center of Hong Kong life once a
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        back to watch the bananas grow. Hong Kong’s third largest island has a
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        4,000 years, and the island is known as “Hong Kong’s Stone Age Island.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        rise of Hong Kong, Macau became an isolated Portuguese outpost.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        little more like Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        the Shun Tak Centre, 200 Connaught Road, Central, in Hong Kong.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Entry procedures are similar to those in Hong Kong — most
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        currency, the pataca, is pegged to the Hong Kong dollar, and you can
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        use your Hong Kong currency freely in Macau.
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        arrive from Hong Kong is the first surprise to greet visitors to
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        wildly popular with the Chinese of Hong Kong, and they make up nearly
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Like Hong Kong, Macau is a duty-free port. It is famous
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        There are many package tours to Guangzhou from Hong Kong
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Turbo Cat ferries leave the China Hong Kong City (CHKC) terminal twice
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        information). Hong Kong currency is widely accepted in Guangzhou, or
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Guangzhou, like Hong Kong, is primarily
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        the answer to Hong Kong. From a population of 20,000 it has grown into
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Because Shenzhen is much cheaper than Hong Kong, it is a
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        popular weekend destination for Hong Kong’s Chinese, who come to relax,
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        Cat ferry makes a one-hour trip (7am–7pm) from Hong Kong’s Macau Ferry
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        than Hong Kong. It is known for its inexpensive (but well-made)
./written_2/travel_guides/berlitz1/WhereToHongKong.txt:        knock-off designer goods. You can use your Hong Kong dollars here, so
./written_2/travel_guides/berlitz2/California-WhereToGo.txt:Portsmouth Square, between Clay and Washington streets, was the city’s original town square, where Sam Brannan announced the discovery of gold in 1848 (see page 16). But what really grabs your attention is the chatter of Chinese voices, the crowds, the color, the smells of five-spice and dried shrimp — it’s a little corner of Hong Kong right in the middle of California.
./written_2/travel_guides/berlitz2/Canada-WhereToGo.txt:East of Robson Square, the Granville Mall pedestrian shopping zone takes you down to the Harbour Centre and the waterfront. From the foot of Granville Street, take a bargain cruise on the commuter Seabus, which crosses Burrard Inlet to North Vancouver, 12 minutes each way. Besides the “fish-eye view” of the city and harbor, you get a close-up of the grand Canada Place, jutting out into the harbor like an ocean liner, with a hint of the port’s 19th-century beginnings in its white simulated sails. Originally the national pavilion at Expo ’86, it is now the B.C. Convention Centre. If you don’t have a taste for the down-and-out life of Skid Row on Hastings Street, make your way east to the brighter colors of Chinatown along Pender Street. Canada’s largest Chinese community, made up of the descendants of immigrants who worked on the Canadian Pacific Railway, is much in evidence in the fruit and vegetable markets, fish-stalls, and boutiques of silks and satins, bamboo and lacquer wares from Hong Kong, Taiwan, and mainland China. Look for the shops of traditional spices and medicines, where reindeer horn and deer’s tail-tips are said to perk up even the weariest husband. Barbecued pork and poultry glisten in the windows of the dozens of restaurants, and tourists are drawn in by the garish street décor — even the telephone booths have pagoda-style roofs.
./written_2/travel_guides/berlitz2/China-WhereToGo.txt:Facing the river along Zhongshan Road are some grandiose old buildings, a bit the worse for wear. These include the Peace Hotel; the Seamen’s Club, formerly the British consulate; and the massive 1923 headquarters of the old Hong Kong and Shanghai Bank, recently renovated and transformed into a Chinese bank, with the separate entrances for Chinese and Europeans eliminated. And east across the river is new East Shanghai, known as Pudong, where construction is booming and where you can enjoy a view from the top of Asia’s tallest structure.
./written_2/travel_guides/berlitz2/China-WhereToGo.txt:Shenzhen (Shumchun), Guangdong Province. Veteran travelers remember Shumchun merely as an undistinguished border town on the Hong Kong–Canton railway line. However, it is now the center of a Special Economic Zone for joint industrial ventures with capitalists from Hong Kong and Macau. With beaches and hot springs, its tourist potential is also rapidly being developed. Day tours from Hong Kong offer Shenzhen as a glimpse of life in China, but its position in an economic buffer zone makes it atypical.
./written_2/travel_guides/berlitz2/China-History.txt:In 1839 the Chinese government finally cracked down on this drain on the treasury, which was also causing mass addiction among the Chinese. Some 20,000 chests of opium were confiscated from British merchants in Guangzhou (Canton). Retaliation came a year later in the first of the Opium Wars, which culminated in a series of “unequal treaties” forced on an increasingly weak Manchu regime. China was obliged to open major ports to foreign political and economic penetration; Hong Kong was ceded to Britain.
./written_2/travel_guides/berlitz2/China-History.txt:In 1992 “Supreme Leader” Deng Xiaoping set into motion a rapid Westernization of China’s economy. Deng’s death and Hong Kong’s return to Chinese sovereignty in 1997 together marked another new era in the creation of a New China, this time as an economic superpower designed to rival the US and Europe in the 21st century. 
./written_2/travel_guides/berlitz2/Beijing-WhatToDo.txt:Carpets. Chinese carpets of silk or wool should be inspected carefully. The colors should not be fading and the threads should be fine and tightly woven. Handmade carpets from the far western provinces and from Tibet are popular in Beijing. Begin shopping at the Friendship Store or the Beijing Carpet Import and Export Corporation on the first floor of the Hong Kong Macao Center (Third Ring Road East).
```
- Explanation:
We search for pattern "Hong kong" case sensitively within ./written_2 directory files and including its sub-directories. This is useful when you do not know what the files is located at which directory, using `-r` will help you find all. This will fix the problem that occured using `-i`, `-l`, `n` on directories.  
