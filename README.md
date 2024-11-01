# Latar Belakang
Transjakarta adalah sistem Bus Rapid Transit (BRT) pertama di Asia Tenggara dan Selatan yang beroperasi sejak 2004 di Jakarta, Indonesia. Transjakarta dirancang sebagai transportasi massal untuk mendukung aktivitas ibukota yang padat. Dengan jalur terpanjang di dunia (251,2 km) dan 260 halte di 13 koridor, Transjakarta yang awalnya beroperasi dari pukul 05.00 - 22.00 WIB, kini beroperasi 24 jam. Dengan rute yang semakin luas dan kemudahan penggunaan, Transjakarta menjadi transportasi favorit warga Jakarta. Namun, ada beberapa masalah yang harus ditangani, seperti kekerasan seksual terhadap perempuan, penumpukan penumpang di halte, kepadatan penumpang di dalam bus, dan pencopetan.
# **Pernyataan Masalah**
Transjakarta ingin mengevaluasi transaksi selama satu bulan pada April 2023 untuk meningkatkan layanan kepada penumpang.
# **Profil Data**
Data ini adalah data penumpang untuk bulan April 2023. Data ini terdiri dari 37.900 baris dan 22 kolom. Kolomnya sebagai berikut:
1.	transID: Unique transaction id for every transaction
2.	payCardID: Customers main identifier. The card customers use as a ticket for entrance and exit.
3.	payCardBank: Customers card bank issuer name
4.	payCardName: Customers name that is embedded in the card.
5.	payCardSex: Customers sex that is embedded in the card
6.	payCardBirthDate: Customers birth year
7.	corridorID: Corridor ID / Route ID as key for route grouping.
8.	corridorName: Corridor Name / Route Name contains Start and Finish for each route.
9.	direction: 0 for Go, 1 for Back. Direction of the route.
10.	tapInStops: Tap In (entrance) Stops ID for identifying stops name
11.	tapInStopsName: Tap In (entrance) Stops Name where customers tap in.
12.	tapInStopsLat: Latitude of Tap In Stops
13.	tapInStopsLon: Longitude of Tap In Stops
14.	stopStartSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
15.	tapInTime: Time of tap in. Date and time
16.	tapOutStops: Tap Out (Exit) Stops ID for identifying stops name
17.	tapOutStopsName: Tap out (exit) Stops Name where customers tap out.
18.	tapOutStopsLat: Latitude of Tap Out Stops
19.	tapOutStopsLon: Longitude of Tap Out Stops
20.	stopEndSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
21.	tapOutTime: Time of tap out. Date and time
22.	payAmount: The number of what customers pay. Some are free. Some not.
# **Link Tableau**
https://public.tableau.com/views/RekomendasiPeningkatanlayananTJ/Story?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 
