# airFreyr JAVA (mark1 / pre-alpha)

Convert Apple Music Albums to iPod Classic-ready m4a music! (Pronounced: air fryer, like the kitchen tool)

## LEGAL DISCLAIMER!

Please ONLY use this software to download music you already own. Downloading music that you do not own IS piracy and you CAN be prosecuted in a court of law.

I DO NOT take responsibility or any illegal actions that may be committed through the use of this program.

## Installation

Building from source is the only way to install this package.

"SOURCE_FOLDER" will usually be "airFreyr"

```bash
git clone https://github.com/zogdog9000/airFreyr.git

Cloning into 'SOURCE_FOLDER'...
remote: Enumerating objects: done.
Receiving objects: 100% | 3.66 MiB/s, done.
Resolving deltas: 100% | done.
```

Alternatively you can download from this webpage by clicking on the green button at the top of this page.

## Usage

```bash
cd "SOURCE_FOLDER"

username@computer SOURCE_FOLDER % java -cp .:gson-2.10.1.jar AirFreyr.java "APPLE_MUSIC_URL"

         _      ______
  ____ _(_)____/ ____/_______  __  _______
 / __ `/ / ___/ /_  / ___/ _ \/ / / / ___/
/ /_/ / / /  / __/ / /  /  __/ /_/ / /
\__,_/_/_/  /_/   /_/   \___/\__, / /___ _    _____
                            /____// /   | |  / /   |
                             __  / / /| | | / / /| |
                            / /_/ / ___ | |/ / ___ |
                            \____/_/  |_|___/_/  |_| [MARK1]

(c) Jake Prescott (zogdog9000) - airFreyr JAVA

🛎️  Checking dependencies + preferences
🛎️  Contacting Apple Music...
    ‼️ Connected to Apple Music

[you get the picture :)]
```

## Contributing

First off, I am in no way a programmer. I'm a groundskeeper who wanted to use his old iPod again. This is the product of a couple of weekends spent on StackOverflow to try to stick something together with tape and glue to download music that I have on CD, but I no longer have a CD drive to rip.

Feel free to make any changes you'd like! I've found that the search algorithm is unreliable in certain edge cases and tends to give music videos more often than it will give audio-only tracks. I am currently working on this. 

I did optimize this code with Claude Sonnet 4 after I got the first version working. The Sonnet-enhanced version (this repository) contains a much cleaner code and is easier for beginners to make their own changes to (Not that it would be any different for a more seasoned programmer to read or edit). If that's not your style and you prefer to see what I scrawled out in my IDE with very minimal documentation and less readability, go ahead. That repository is available at [zogdog9000/airFreyrClassic](https://lolwut.com) and WILL NOT be maintained. 

Thanks for taking the time to check out a lil' project by a crazy midwesterner. I hope you'll love breathing new life into your iPods like I did! Props to [miraclx for freyr-js, the inspiration / cause for this project!](https://github.com/miraclx/freyr-js)

## License

[MIT](https://choosealicense.com/licenses/mit/) !!! Again, please make sure you are using this software for a legitimate use and that you own all music being downloaded.
