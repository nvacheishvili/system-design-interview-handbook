# [System Design Glossary](https://www.udemy.com/course/system-design-zero-to-hero/?referralCode=183D59A1EBE9E71D26FF)

Every term from the course in plain words, A to Z.

[Download as PDF](pdf/System-Design-Glossary-Whole-Course.pdf)


## #

- **304:** A status code that means not modified.
- **404:** A status code that means not found.
- **429:** The HTTP code for too many requests.

## A

- **A\*:** A search that picks the smallest time so far plus a guess of the time that's left. Say it as A star.
- **Acceleration limits:** Limits on a sharp increase in usage. Our reasoning is that chips can't just appear in a minute.
- **Access control list (ACL):** A list of who can do what.
- **ACID / transaction:** Atomic, consistent, isolated and durable. A group of steps that works like this is called a transaction.
- **Acknowledgment:** The "got it" message a server sends back.
- **Acks:** Short for acknowledgments. Kafka's setting for how long a producer waits for got it. All is the default today.
- **Adaptive bitrate streaming:** The quality adapts to your connection, one small request at a time.
- **Adjacency list:** An address book for each junction, listing its roads going out.
- **AES:** The Advanced Encryption Standard, published by the United States government in 2001, a strong and well-tested way of scrambling data.
- **Agent:** A tool that acts for a person.
- **Aggregate location data:** Data from a lot of phones added together.
- **Aggregated and anonymized:** Only totals, with no names on it.
- **Aggregating:** A fancier word for adding things up.
- **AirTag:** Apple's tracker tag, about the size of a coin.
- **AJAX:** An old name for a page asking for something in the background, without reloading.
- **Algorithm:** A step by step way of doing something.
- **Allocated:** How much space we've promised, which isn't how much is being used.
- **Ambiguity:** The question is vague, and it could mean a lot of different things.
- **Analytics:** Counting and studying what people do.
- **Ancestors:** The dots on the path above you, like your parent and your parent's parent.
- **Anti-entropy:** Servers quietly comparing and fixing their copies in the background. Entropy is things slowly drifting into disorder.
- **Apache Cassandra:** A popular open source database whose machines sit on a ring. It calls each spot a token.
- **API:** A way for one program to request something from another.
- **API gateway:** A service in front of your APIs that handles jobs they all need, like checking who's calling, and rate limiting.
- **APNs:** Apple Push Notification service. The service that delivers messages to iPhones.
- **Appeal:** Someone can ask for another look.
- **Approximate location:** A blurry location. Android's docs say it's within about 3 square km, and Apple has said a typical value is around 5 km.
- **As the crow flies:** Straight line distance.
- **ASCII:** An old table where every character is a number, so capital A is 65. It only has 128 characters, so each fits in 1 byte.
- **Assumption:** A number you decide to go with because you don't know the real one. You share it with your interviewer.
- **Asynchronous:** Sender and receiver don't have to work at the same time. Like texting a friend.
- **At least once:** We keep trying until we know a message was accepted, so it might arrive more than once.
- **At most once:** Each message gets processed 1 time or 0 times.
- **Atomic:** It either happens all at once, or it doesn't happen at all, and nobody can see it halfway through.
- **Auth token:** A long secret string our server gives an app at login, which basically says, this is Ben.
- **Authentication:** Proving who you are.
- **Auto increment:** The database has a counter. It gives a new row the next number, then adds 1.
- **Auto scaling:** Adding or removing web servers automatically based on traffic.
- **Autocomplete:** The little list under a search box. You'll also hear typeahead, and search as you type.
- **AV1:** A newer codec from the Alliance for Open Media, free to use.
- **Availability:** How much a system is up, written as a percentage of uptime.
- **Availability (in CAP):** Every request gets an answer and not an error, even if the answer is out of date.
- **AWS:** Amazon Web Services. A service provider that offers infrastructure like servers, storage and databases.

## B

- **B-tree:** The common kind of tree in databases, with a lot of branches on each level. It's the default in PostgreSQL, and you most probably won't be asked how it works.
- **Back of the envelope calculation:** A quick, approximate estimate, with math simple enough to do on the back of an envelope. The goal is a feel for the scale, not precision.
- **Back queues:** The per-website lines: being polite.
- **Backend:** Everything that runs on our side, like the servers and the data.
- **Background:** You're not looking at the app, so it's in your pocket.
- **Bandwidth:** How much data can move through a connection each second.
- **Base:** How many digits you have before a wheel rolls over. Base 10 has 10, and base 2 has 2.
- **Base 32:** 32 symbols on each wheel of our odometer. Each character is 5 switches.
- **Base 62:** Counting with 62 digits: 0 to 9, a to z, then capital A to Z.
- **Batch:** A pile of work that you do all at once.
- **Batch API:** You send a huge pile of requests, and you get the answers back within a day, for half the price.
- **Bidirectional:** Two-way, so both sides can send.
- **Big O:** A short way of saying how much the work grows when the data gets bigger.
- **Binary:** Zeros and ones, which is how computers operate.
- **Binary file:** A compact format made for computers, and not text a person would read.
- **Birthday surprise:** With just 23 people in a room, it's about a coin flip that 2 share a birthday. Collisions come much sooner than you'd expect.
- **Bit:** A single zero or one.
- **Bitrate:** How much data a video uses for each second. Like water going through a pipe.
- **Black box:** Something we use from the outside, and we don't care what's inside.
- **Blob storage:** Another name for object storage, used by Microsoft's cloud. A blob is just a big file.
- **Block:** A piece of a file. Each piece is the same size, and each one gets a fingerprint.
- **Block server:** One of our own servers that sits in the middle and takes the blocks.
- **Bloom filter:** A row of lights in memory that answers definitely not, or maybe. Named after Burton Bloom.
- **Blue green:** You build a whole new set right beside the old one, check it, and then switch people over.
- **Bluetooth:** The short-range radio that connects your headphones to your phone.
- **Bookmark:** Our name for one small number a device keeps for a chat: the last message number it has. Also: The number that each reader keeps, to know where it's up to.
- **Bot:** A program that visits websites by itself. A crawler is one.
- **Bottleneck:** The one part of a system that slows everything else down, like one narrow door in a very busy store.
- **Breadth first:** Read everything on this page first, then everything those pages link to. Breadth means how wide something is.
- **Broker:** A go-between that takes messages from one side and hands them to the other.
- **Brute force:** Trying every possible answer until one of them works.
- **Buffer:** A small area in memory, like the 2 trays on the desk. In Mercator, those trays held only 600 links each. Also: The little stock of video that the player keeps ready to play.
- **Burst:** A lot of requests arriving at once.
- **Byte:** 8 bits. Enough for about one English letter. Emojis and many other alphabets take a bit more.

## C

- **Cache:** Temporary storage for frequently used data, or responses that were expensive to get.
- **Cache miss:** The cache doesn't have the answer, so we have to go to the database.
- **Cache-Control:** A header that controls how long a browser remembers an answer.
- **Candidates:** The posts that could possibly be shown. Also: A few good routes that the route planner finds. You might hear this called top K shortest paths, where K is just a number.
- **CAP theorem:** When servers can't talk to each other, you have to choose between staying correct and staying available.
- **Capacity:** How many places a square can hold. It's a number we pick when we build the tree.
- **Capacity estimate:** Figuring out how much storage or memory a system needs.
- **CDN:** Content delivery network. Servers spread across locations that deliver static content.
- **Cell tower:** The antenna that your phone connects to for calls and data.
- **Certificate:** Like an ID card for our server.
- **Change list:** A list for each shared folder, where every commit adds one line with the next number.
- **Channel (pub-sub):** The station in pub-sub. Anyone tuned in hears what's sent, and it doesn't keep anything.
- **Checkpoint:** Writing down where you are on storage that survives the machine. It's like saving your game.
- **Children / parent:** The dots right below a dot are its children, and the dot right above is its parent.
- **Chip:** The piece of hardware that does the actual computing.
- **Chromium:** The free, open source browser project that Google's Chrome browser is built on.
- **Client:** The computer or app asking the server for something.
- **Clockwise:** The direction that the hands of a clock move.
- **Cloudflare:** A company that a huge number of websites put in front of their servers, to protect them from attacks and speed them up.
- **CloudFront:** Amazon's CDN. Its public price page for the United States starts at about 8.5 cents a gigabyte, and goes down to 2 cents past 5 petabytes in a month.
- **Cluster:** A big group of machines being run together.
- **Clustering key:** The part of a key that sorts things inside a folder. The partition key decides the folder.
- **CMAF:** A format that lets both menus point at one set of files. You probably won't get asked about it.
- **Codec:** The method for squeezing a video, from coder and decoder. Some detail is thrown away for good.
- **Coins:** Our name for a rate limiter's tokens, which have nothing to do with text. I'd say that out loud in your interview.
- **Cold storage:** Cheaper storage that's slower to get back. Cold just means rarely touched.
- **Collapse ID:** If you send a notification with one, Apple can merge it with an earlier one that has the same ID. Google has something similar. It won't help with a text.
- **Collision:** 2 different things get the same ID.
- **Commit:** The last step of the conversation, which means that it's now real.
- **Commit log:** The notebook on disk. Every change gets added at the very end, so it survives a power cut.
- **Committed (a message):** When everyone on the in-sync list has it, so it's safe.
- **Committing (a bookmark):** A reader saving its place by telling the coordinator, I've finished up to here.
- **Common Crawl:** A non-profit that crawls the web and gives the results away for free, so researchers don't need a crawler of their own.
- **Compaction:** Merging a few boxes into one new box and throwing the old ones away. Also: Asking the model to write a short summary of the old part, and sending that instead.
- **Compare-and-set:** One step that nothing can interrupt: set the latest to 10, only if it's still 9. One wins, and the other gets told no.
- **Compiler:** The program that turns code into something a chip can run.
- **Composite key:** A key made of two parts.
- **Compression:** Squeezing data to take less space, like a zip file.
- **Compute power:** The CPU and memory that do the actual work.
- **Conflict:** Neither version is older. Each one knows about a write the other one doesn't.
- **Conflicted copy:** Dropbox's name for the file that keeps the loser's work, right next to the original.
- **Connection server:** Our name here for the servers that hold everybody's open lines, like WhatsApp's chat servers.
- **Consistency (in CAP):** Everyone sees the same, latest data.
- **Consistent hashing:** Finding a server by walking around a ring. It's called consistent because when the servers change, most of the answers stay the same.
- **Consumer group:** A group of readers that share the work, where each partition goes to only one member.
- **Consumer lag:** How far a reader's bookmark is from the end of the book. It's probably the first thing I'd put on a dashboard.
- **Container:** The box that holds the video, the sound and maybe subtitles. That's what .mp4 is, so it doesn't tell you the codec.
- **Content ID:** YouTube's system for finding copies of other people's work. Copyright owners submit their files to a database, and new uploads are compared to it.
- **Content Seen:** The box that asks: have we already seen these exact words somewhere else?
- **Content-defined chunking:** Cutting a file by what's in the content, instead of by position.
- **Context:** Everything that the model has in front of it.
- **Context window:** The total a model can look at, including the answer it's writing.
- **Continuous batching:** Letting people step on and off between steps. The paper called it iteration-level scheduling, where iteration means one trip around the loop.
- **Continuous integration:** Each code check-in is automatically verified, so teams detect problems early.
- **Contraction hierarchies:** A research idea where you add shortcut arrows ahead of time. You probably won't be asked how it works.
- **Control plane:** The part of Kubernetes that makes those decisions, like a manager's office.
- **Controller:** The machine with the job of deciding who's the new leader.
- **Coordinator:** Whichever server takes the request, like a waiter passing your order to the kitchen. Any server can do this.
- **Corrupt:** Damaged. A corrupt file fails on every worker.
- **CP / AP:** CP stays correct during a partition. AP stays available.
- **CPU:** Central processing unit. The brain of a computer, which runs instructions and calculations.
- **CPU bound:** When the thing that limits you is how fast the machine can work, and not how much it can hold.
- **CPU cache:** A tiny, very fast memory right next to the processor.
- **CRC:** Cyclic redundancy check. A small number worked out from a batch's bytes and saved with them. If it doesn't match later, something got damaged.
- **Cron job:** A program set to run on a schedule, like the alarm on your phone.
- **CRUD:** Create, read, update and delete.
- **CSS:** The code that controls how a website looks.
- **Cursor:** A little marker that says where we stopped, so that new posts on top don't shift the page.

## D

- **Daily active users:** People who open the app on any given day.
- **Dark launch:** Running a new limit so it decides but doesn't block anybody, and only writes down what it would have blocked. Also called shadow mode.
- **DASH:** An international standard that no single company owns, and it became a standard in 2012. It does the same job as HLS, and its menu just looks different.
- **Data center:** A building full of servers.
- **Data retention:** How long we keep the data for. The longer the retention, the larger the total storage we need.
- **Data scraping:** Using programs to automatically copy large amounts of data from a website.
- **Data structure:** A way of arranging data so that one kind of question gets easy.
- **Database replication:** Keeping copies of your database on more than one server.
- **Dead letter queue:** A separate line for messages we gave up on, so they don't block anyone, and a person can look at them.
- **Dead reckoning:** An old word from ships, for working out where you are from your speed and direction when you can't see anything.
- **Debouncing:** Only sending a request once someone has stopped typing for a moment. Like an elevator door, which only closes when nobody's come in for a little while.
- **Decoupling:** The sender doesn't care how fast the receiver is, or whether it's online.
- **Deduplication:** Keeping one copy of something that shows up many times. Also called dedupe.
- **DeepMind:** Google's AI research lab.
- **Delayed message:** A message that should show up later, and not now.
- **Delta sync:** You only send the difference. Delta is a word for the difference between 2 things.
- **Denial of service attack (DoS):** Flooding a system on purpose, so that real users can't get in.
- **Denormalization:** Intentionally adding duplication, so queries don't have to join many tables.
- **Depth first:** Keep going deeper before you ever come back up.
- **DESC:** Short for descending, so biggest first.
- **Design deep dive:** Going into a lot more detail on the parts that matter.
- **Detecting Unwanted Location Trackers:** A shared specification from Apple and Google. If an unknown tag is seen moving with you, your phone can warn you.
- **Device token:** A long string of letters and numbers that Apple or Google gives to our app on a phone. A delivery address only the courier understands.
- **Dijkstra's algorithm:** A search that always finishes the closest unfinished junction next, named after Edsger Dijkstra, a Dutch computer scientist.
- **Directed acyclic graph (DAG):** Dots and arrows where the arrows go one way (directed), and you can't follow them back to where you started (acyclic).
- **Disk:** Long-term storage, like hard drives or solid state drives. Data stays there even after the power is off, but it's much slower to access.
- **Disk seek:** When a hard drive has to move to the right spot before it can start reading.
- **Distributed environment:** Running on many machines instead of one.
- **Distributed message queue:** A message queue that runs across a lot of machines.
- **Distributed storage:** Spreading your data across many machines.
- **DNS:** Domain Name System. Translates names like google.com into IP addresses, like the contacts on your phone.
- **Downloader:** The program that actually fetches pages.
- **Downstream:** Anything further along that the request would have gone to next.
- **Draining:** Telling a server to stop taking new people, and waiting for it to empty.
- **DRM:** Digital rights management. How paid films usually work.
- **Durability:** Once it's saved, we don't lose it.
- **Durable:** Messages are safely kept, so they aren't lost.
- **Dynamic rendering:** A website sends crawlers a different version of its page.
- **Dynamo:** A storage system Amazon built for its own use, including its shopping cart. It uses a ring with virtual nodes.

## E

- **E.164:** The standard phone number format: a plus, a country code, then the rest of the number, with at most 15 digits.
- **EC2:** The AWS service that rents out servers.
- **Edge location:** One of many locations close to users where a system runs something, like limiters.
- **Elasticsearch:** A popular search engine you can add to your own system, with a built-in feature for search as you type.
- **Elixir:** A newer language that runs on the same engine as Erlang.
- **Encoding:** Squeezing a video with a codec.
- **Encoding on demand:** Making a version only when someone asks for it and it isn't there.
- **Encrypted:** Scrambled, so that it can't be read without a key.
- **Encrypted at rest and in transit:** Encrypted on the company's disks and on the road.
- **Encryption at rest:** Each block gets scrambled before it's stored. The company holds the key, so it can still make previews, search and dedupe.
- **Encryption in transit:** Encrypted on the road. That's HTTPS, and it stops anyone on the café wifi.
- **Encryption on the device:** The file gets locked before it leaves Anna's phone, and the company never gets the key.
- **End-to-end encryption:** A message stays locked the whole way from one device to the other, so nobody in between can get to the content.
- **Endpoint:** One specific address you can send a request to. One item on the API's menu.
- **Epoch:** The moment we start counting time from. It's like a birthday.
- **Equator:** The ring around the very middle of the Earth.
- **Erlang:** A programming language made for running a huge number of small things at the same time.
- **ETA:** Estimated time of arrival.
- **etcd:** A small and reliable key-value store for keeping that same kind of information, which also uses Raft.
- **Event ID:** One ID for this one thing that happened, so that every retry carries the same ID.
- **Eventual consistency:** Copies can disagree for a moment, but they catch up. Also: If people stop making changes, all of the copies end up the same, with no exact time on it.
- **Eviction:** Removing an existing item to make room for a new one.
- **EXPIRE:** A Redis command that deletes a key after a certain number of seconds.
- **Expiry:** A time after which a message isn't worth sending.
- **Explore and Reels:** Instagram's discovery and short video sections. Mosseri says most of what you see there comes from accounts you don't follow.
- **Exponential backoff:** Waiting longer after each failure: 1 second, then 2, then 4.
- **Extensibility:** Designing so that you can add something new without redoing everything.

## F

- **Failing closed:** If the limiter breaks, reject every request.
- **Failing open:** If the limiter breaks, let every request through.
- **Failover:** If one machine fails, another takes over. Swapping in the spare tire.
- **False positive:** The answer looked like a yes, and it was wrong.
- **Fan-out:** One request or one thing spreading out to a lot of places, like a fan opening up.
- **Fan-out on read:** Doing that spreading out when somebody reads.
- **Fan-out on write:** Doing the spreading out when somebody writes a post.
- **FCM:** Firebase Cloud Messaging. Firebase is Google's set of tools for people who build apps, and this is the part that delivers messages.
- **Feature flag:** A switch that lets you turn new code on slowly.
- **Feed:** The list you scroll when you open the app. It's different for every person, because it's built from the people they follow.
- **FFmpeg:** A free tool for pretty much any job with video and sound files.
- **FIFO:** First in, first out. Things leave in the order they arrived, like a line at a coffee shop. Also: First in, first out. A normal line, where whoever arrived first gets served first.
- **Filter:** A short list of things we never show. Every answer goes past it on the way out.
- **Find Hub:** Google's version of this network.
- **Find My:** Apple's app for finding your devices, your things and your friends.
- **Fingerprint:** A hash used as one short number that stands for something bigger. Change even one letter, and you almost certainly get a different number.
- **Firewall:** Like a security guard at the edge of a network, who only lets certain traffic through.
- **Fixed window counter:** Cuts time into windows, gives each customer a counter, and resets it when the next window starts.
- **Flink:** Keeps running counts on a stream as it goes by.
- **Flush:** Writing the desk out to disk.
- **For You feed:** What you land on in TikTok: a stream of videos curated to your interests.
- **Foreground service:** What an app runs to get more location updates. It shows a notification on the screen the whole time, so you know it's happening.
- **Foreign key:** A column that points to a row in another table.
- **Forged:** Faked.
- **Forward:** One update being passed along to one friend's connection.
- **Frame:** One still picture in a video, like one page of a flipbook.
- **Frame rate:** How fast you flip, in frames per second. 30 or 60 is normal.
- **Frequency cap:** A limit on how many messages of a certain kind one person gets in a day or a week.
- **Front queues:** The importance lines: what matters.

## G

- **Garbage collection:** Sweeping up what nobody's using anymore, like the blocks from when Dan gave up in the tunnel.
- **GDPR:** The European Union's privacy law, which names location data in its definition of personal data. Nothing here is legal advice.
- **Geocoding:** Turning words into a latitude and a longitude.
- **GeoDNS:** A DNS service that gives back a different IP address based on the user's location.
- **Geofence:** A shape on a map with a rule attached, so that something happens when you go in or come out.
- **Geohash:** An address for a square. Each cut writes down which piece you went into.
- **GEOSEARCH:** A Redis command. Places are kept in a sorted set, a list in order by a score, with a geohash as that score.
- **GET / POST:** GET means give me something. POST means here's something new, please save it.
- **Ghost Mode:** Snapchat's setting that hides you from everyone on its map, with a timer of 3 hours, 24 hours, or until you turn it off.
- **Gigabyte (GB):** 1,024 megabytes. Round it to a billion bytes.
- **GIS:** Geographic information system. The general name for software that works with maps.
- **Glacier:** Amazon's cold storage. The slowest one, Deep Archive, can take 12 hours to get something back, or up to 48 on its cheapest setting.
- **Google Drive / Dropbox:** Google's service for keeping your files online, and a company built around the same idea.
- **Google Play services:** Google's own software that comes on most Android phones.
- **Google-Extended:** A setting in your robots file for whether what Google crawled can train Gemini, its AI model.
- **Gossip:** Servers telling a few random servers what they know, so news spreads like an office rumor. That's the real technical word.
- **GPS:** Global Positioning System. A group of satellites run by the US government, each one broadcasting where it is and what time it is.
- **GPU:** Graphics processing unit. A chip that does a huge number of small calculations at once, first built to draw video game graphics.
- **Graph:** Dots and arrows. It isn't the kind with a line going up from math class.
- **Graph database:** A database built around dots and arrows.
- **Graph neural network:** A kind of machine learning Google used with DeepMind. It fits because roads are a graph, and traffic on one road spills onto the next.
- **Group coordinator:** One broker that looks after one consumer group. It knows who's in the group and where their bookmarks are.
- **Group leader:** Whichever member got picked to make the plan. It has no other power.
- **Group of pictures (GOP):** A keyframe and the changes that follow it.

## H

- **H.264:** The older codec that almost everything can play.
- **H3:** Uber's grid of hexagons covering the whole planet.
- **Hadoop and Spark:** Open source tools for running big jobs across a lot of machines, so you don't have to write all that splitting up yourself.
- **Hallucination:** When a model writes something that sounds completely sure of itself and is just wrong.
- **Handshake:** A quick hello between two sides at the start of TCP. After that, they have a connection.
- **Hard limit:** A limit that can never be passed.
- **Hash function:** A formula that turns a value into a number.
- **Hash ring:** The circle that servers and keys sit on. Also just called a ring.
- **Hash space:** All of the possible spots together. Ours has 12, and real rings have billions and often way more.
- **Hash table:** The dictionary programmers use all the time. A hash function gives you the hook number, so you jump straight there.
- **HBase:** An open source database for spreading data over many machines.
- **Headers:** Small pieces of information that travel along with a response. The user doesn't see them, but the program on the other side does.
- **Headless browser:** A real browser without a screen.
- **Health check:** A small request sent to each server on a schedule, to see if it's still answering.
- **Heap:** A sorted list that gives you the earliest one quickly. Also: It only promises that one specific thing is always on top.
- **Heartbeat:** A phone keeps sending a tiny message that says, still here. As long as it keeps going, you're alive.
- **Heartbeat counter:** One number a server keeps about itself and adds to regularly. As long as it keeps going, you're alive.
- **Heatmap:** A map of where people have been active, with busy places glowing brighter.
- **Helper:** A small piece of code for each open line. It holds the line, remembers that person's newest spot, and subscribes to their friends' channels. Also called a connection handler.
- **Herd effect:** Google's name for programs all coming back at the same time and hitting the same thing. It's our retry storm.
- **HEVC:** A newer codec, also called H.265, with licensing fees.
- **Hexadecimal:** Counting with 16 symbols, 0 to 9 and then a to f. Each symbol stands for 4 bits.
- **Hierarchy:** Levels. Here, small roads, bigger roads and highways.
- **High availability:** A system stays up and running without interruption for as long as possible.
- **High level:** The big picture: the main boxes and how they connect, without the details of each one yet.
- **High watermark:** The line that readers can read up to. You only need to recognize the name.
- **Hilbert curve:** A line you can draw without lifting your pen. It goes through every square once, and every step goes to a square that touches the last one.
- **Hint:** A note saying this copy really belongs to another server.
- **Hinted handoff:** A server holds a copy with a hint, then hands it back when the real owner returns.
- **HLS:** HTTP Live Streaming, which came from Apple. A menu and pieces.
- **Hot partition:** Everyone is reading the same busy chunk of data, so it all lands on one partition. It's one very popular key again.
- **Hotspot key:** Another name for the celebrity problem.
- **HTML:** The file that describes what a page looks like.
- **HTTP request:** A message your computer sends to a web server asking for something.
- **HTTPS:** The secure kind of web connection.
- **Hybrid:** Most people's posts get written ahead of time, and celebrity posts get fetched when you open the app.
- **Hydration:** A funny word for filling in the rest. You start with something dry, only the numbers, and you add everything else.

## I

- **I/O:** Input and output. Reading from and writing to something like a disk.
- **Idempotency:** Doing something twice has the same effect as doing it once.
- **Idempotent producer:** If a producer sends again, the broker notices the repeat, and only 1 copy goes in the log. It's on by default now.
- **Immutable:** Can't be changed.
- **In-sync replicas (ISR):** A live list the leader keeps of who's caught up.
- **INCR:** A Redis command that adds 1 to a counter and gives you back the new number. If the counter doesn't exist yet, it starts from 0.
- **Index:** A sorted list a database keeps so it can find a row without reading the whole table, like the list of topics at the back of a book.
- **Inference:** Using the model to answer someone. It just means running the loop.
- **Input / output:** The text you send in, and what the model writes.
- **Input method editor:** You type on a normal keyboard with letters, then choose the characters you meant. Often used in languages like Chinese and Japanese.
- **Internal node:** A dot with children. It only holds directions.
- **Internet Archive:** A non-profit library that saves copies of web pages. Its tool for looking at old copies is called the Wayback Machine.
- **Interpolation:** Working out a spot between 2 you know, like number 50 being about halfway along a block.
- **Invalidate:** Tell the CDN to remove a file.
- **IP address:** A set of numbers that tells other machines where to find a machine, like a home address.
- **ISP:** Internet service provider. A company that sells people their internet connection.
- **Item:** The things you see in a folder. A file and a folder are both items.

## J

- **Jitter:** A little randomness added to a wait, so that retries don't all come back together.
- **Join:** Combines rows from two or more tables based on a related column.
- **JSON:** JavaScript Object Notation, a simple text format for sending data.
- **Junction:** A place where roads meet.

## K

- **K nearest:** Finding the closest K of something, however far away. K is just a number.
- **Kafka:** Carries a huge stream of events from the programs that write them to the programs that read them, kind of like a giant shared diary.
- **Keep-alive:** Normal HTTP connections staying open. The server still can't say anything until it's asked.
- **Key:** Anything we look up, like Anna.
- **Key-value store:** Saves values under unique keys, like a dictionary. It only knows how to find things by their key.
- **Keyframe:** A whole picture. Everything after it is just a list of changes.
- **Kilobyte (KB):** 1,024 bytes. Round it to a thousand bytes.
- **KRaft:** The design where Kafka does ZooKeeper's job itself, using Raft.
- **Kubernetes:** A very popular open source system for running programs across many machines. It starts them, restarts them when they crash, and moves them around.
- **KV cache:** The model's notes. It stands for key-value cache, and it has nothing to do with our key-value store chapter.

## L

- **Language of nines:** Describing uptime by counting the nines. 99.9% is three nines.
- **Last write wins:** Look at the time and keep the newest version. It's simple, but it can lose an update.
- **Latency:** The delay between sending a request and receiving the response.
- **Latitude:** How far north or south you are. The equator is zero, and the poles are 90 degrees north and 90 degrees south.
- **Layer 3:** The network layer, where we can limit by IP address.
- **Layer 7:** The application layer, where we look at HTTP requests.
- **LBFS:** A research file system built for slow networks, which described this idea in 2001. You probably won't get asked this.
- **Leaky bucket:** A bucket that drains at a steady speed and overflows if you pour too fast. Either a real queue, or just a meter.
- **Leaves:** The bottom of the tree, which are the shelves here.
- **Library:** Code that someone wrote so that you don't have to. Also: Ready-made code that you add to your program, so you don't have to write it.
- **License server:** Checks that you're allowed to watch, and sends back the key and the rules.
- **LIKE:** In a database query, it means match a pattern. The percent sign means anything at all can come after this.
- **List (array):** Like a row of numbered shelves, sitting side by side.
- **Load balancer:** Takes every incoming request and spreads the requests across servers. Like the host at a busy restaurant.
- **Location header:** A header that holds the address to go to.
- **Location-based service (LBS):** A name for anything that answers based on where you are.
- **Lock:** One server says, nobody touch this until I'm done.
- **Log:** A record of what happened. Also: A record of what happened. Here it has 2 rules: only add to the end, and never change what's written.
- **Logarithm:** How many times can you cut this in half until 1 is left? Also shortened to log.
- **Long polling:** You ask, and the server holds on to your request until something happens or time runs out.
- **Long tail:** The thin part of the chart, with the very long list of things that hardly anyone wants.
- **Longitude:** How far east or west you are, up to 180 degrees east and 180 degrees west, which meet on the other side of the world.
- **Low-Latency HLS:** An extension of HLS where the player can get small parts of a piece before the piece has finished. You probably won't get asked how it works.
- **LRU:** Least recently used. Removes whatever hasn't been used for the longest time.
- **Lua script:** A small program you can run in Redis, as one atomic step.

## M

- **Machine learning model:** A program that learned its rules from a huge number of examples, instead of someone writing them by hand.
- **Magic Pocket:** Dropbox's own custom-built storage.
- **Mail Privacy Protection:** Apple's feature to stop senders from learning when you read things. It downloads those images in the background, whether or not you open the email.
- **Majority:** More than half. Only one side of a break can ever have one.
- **Map matching:** Taking a dot and putting it on a road, like a spell check with a dictionary of all the roads. Also called snapping to a road.
- **Map tile:** One of the small squares the map is cut into, like a tile in a mosaic.
- **Master / slave:** The original, which takes writes, and the copies, which serve reads. Also called primary and replica.
- **Max tokens:** A ceiling that a caller can set, that says never write more than this.
- **MD5:** A real hash function. It gives one big number, written as 32 hexadecimal characters.
- **Megabyte (MB):** 1,024 kilobytes. Round it to a million bytes.
- **Memory table (memtable):** The desk: recent changes in memory, used for quick answers.
- **Menu:** A small text file that lists the qualities we have, and the small files for each one.
- **Mercator:** A crawler that 2 researchers at Compaq built around 1999, to work out how a crawler could grow to the size of the web. Also: A projection named after a mapmaker. Sizes are wrong across the world, and shapes are right up close.
- **Merge:** Combining 2 versions into one.
- **Merging:** Making two lists that are already in order into one, by repeatedly comparing the two top items.
- **Merkle tree:** A tree of fingerprints where each one depends on the ones below it. Named after Ralph Merkle.
- **Message queue:** A durable component that helps systems communicate asynchronously. Like a mailbox.
- **Metadata:** Information a message carries about itself, like a message ID, who sent it, who it's going to, and a timestamp.
- **Metrics:** Measurements over time, like CPU, or daily active users.
- **Microsecond:** One millionth of a second.
- **Microservice:** A small separate service that does one job, like the search service.
- **Middleware:** Software that sits between the client and our API servers, and looks at every request before it gets through.
- **Millisecond:** One thousandth of a second.
- **Min in-sync replicas:** A floor. If fewer than this many copies are on the list, refuse the write.
- **Model:** The program that writes the answers.
- **Modulo:** Dividing and taking the remainder.
- **Monthly active users:** People who opened the app at least once in the month.
- **MQTT:** A small protocol designed to go easy on bandwidth and batteries.
- **Multi-master replication:** The name you might see for skipping numbers. Multi means more than one database that accepts writes. No IDs are actually being copied.
- **Multi-region:** Deployed in two or more geographic locations around the world.
- **Multipart upload:** Amazon S3's built-in way to upload in parts, where you only retry the parts that failed.
- **MyRocks:** MySQL with a different way of storing things on disk underneath.

## N

- **N:** The number of copies of each key.
- **Namespace:** A named space that things live in. Dropbox's post uses the word for a space like a shared folder.
- **Nanosecond:** One billionth of a second.
- **Network partition:** A broken connection between servers. Nothing has crashed, they just can't talk.
- **Nginx:** Very popular software for web servers and load balancers.
- **Node / edge:** A dot is a node, and an arrow is an edge.
- **Non-functional requirements:** How well it has to work, and not what it does.
- **Normalization:** Cleaning up what someone typed, like making it lowercase and treating ST as street.
- **Normalizing:** Cleaning up an address before asking if we've seen it, so all of its versions turn into one.
- **Northguard:** LinkedIn's own new system.
- **NoSQL:** A non-relational database. Examples: CouchDB, Neo4j, Cassandra, DynamoDB.
- **Not before time:** The earliest we can go back to a website.
- **Notification:** A message we send to a person, without them asking for it at that moment.
- **NTP:** A way for a computer to ask a trusted clock what time it is.
- **Nudge:** A small message that only says something changed, so that the device goes and asks.

## O

- **O(1):** Constant. The work doesn't grow with the data.
- **O(log n):** The work grows with how many times you can cut the data in half. Each doubling costs 1 more look.
- **O(n log n):** n times log n. What good sorting costs.
- **O(n squared):** n times n. What comparing everyone with everyone costs.
- **O(n):** Linear. Twice the data, twice the work.
- **OAuth:** A standard, and a common way to get a temporary pass instead of handing over your real secret.
- **Object storage:** Online storage built for big files, like Amazon S3. Also: A giant folder for files. You give it a file and a name, and later you ask for that name. An object is just a word for a file. It exists because it's way cheaper and easier than keeping billions of files in a database.
- **Offset:** How many results to skip.
- **Offset (in a log):** A message's position in the log, like a page number.
- **One-click unsubscribe:** Someone can leave a mailing list with a single click, without logging in.
- **Opaque:** The store can't see inside the value, like a coat check that never goes through your pockets.
- **Open source:** Sharing the code with everyone.
- **OpenStreetMap:** A free map of the world that volunteers make and keep up to date. It exists so that nobody has to own the map.
- **Operating system:** The software in charge of the whole phone.
- **Operational transformation / CRDTs:** 2 names for how tools like Google Docs combine small edits. You most probably won't be asked how they work in this question.
- **Opt in:** It's off until someone deliberately turns it on.
- **Opt out:** Just saying no.
- **Origin:** The place where the original file lives, like your web server or Amazon S3.
- **Over-engineering:** Building something way more complicated than the problem actually needs.
- **Overloaded error:** A message that says you did nothing wrong, and they're just full.
- **Overture Maps:** A newer project from companies including Amazon, Meta and Microsoft. It combines open map data so that companies can share that work.
- **OWASP:** A well known non-profit group for web security.

## P

- **Packet:** A small chunk of data that gets sent on its own.
- **Page cache:** The recently used pieces of files that the operating system keeps in spare memory.
- **Page token:** What Google Drive's public API gives you to save for next time. It's the same shape as a bookmark.
- **PageRank:** A score for how important a page is, based on the pages that link to it.
- **Pages (memory):** Small pieces of memory that an operating system hands out as they're needed.
- **Pagination:** Sending the results one page at a time, instead of all of them at once.
- **Pagination token:** A little marker that tells the next request where to continue from. The same idea as an offset.
- **Parsing:** Going through a long string of letters and working out the pieces, like reading a recipe and pulling out the ingredients.
- **Partition:** A stretch of the ring that one server owns. Also: One piece of a topic, like one volume of a book.
- **Partition key:** In Cassandra, the first part of the key. It decides which machine, and the second part sorts the rows on that machine.
- **Partition tolerance:** The system keeps working through a network partition.
- **Partitioning (data):** Splitting your data across servers. Each piece is called a partition.
- **Path:** The address of a file, like book club/week one/notes.
- **Payload:** The actual content that we're sending.
- **Peer to peer:** Devices talking straight to each other, with nothing in the middle. A peer just means an equal.
- **Per-conversation sequence:** Each chat has its own count, so the next message in that chat gets the next number.
- **Perplexity:** An AI search tool.
- **Persistent data store:** One that keeps data even when the power goes off.
- **Petabyte (PB):** 1,024 terabytes, which is about a million gigabytes.
- **Pixel:** One of the tiny colored dots that a picture is made of. Also: One of the tiny colored squares that make up a picture on a screen.
- **Plus Codes:** Google's open source system that turns any spot into a short code, using only math, so a place with no address can still have something you can write down.
- **PNG:** A common image file.
- **Pointer:** Where something is in memory.
- **Poison message:** A bad message that crashes the reader every time, so everyone behind it is stuck.
- **Polling:** You keep asking on a schedule.
- **Polygon:** A shape with straight sides.
- **Pool:** The group of servers behind a load balancer.
- **POP:** Point of presence. One of a CDN's many locations.
- **Port:** Which door of a computer you're knocking on. Secure web traffic normally uses door 443.
- **PostGIS:** An add-on for PostgreSQL, so that a normal database can understand locations and shapes.
- **Postmortem:** A write-up that says what broke and what they're changing, without blaming anybody.
- **Power of two:** A number you get by multiplying 2 by itself repeatedly: 2, 4, 8, 16, and 10 times gets you 1,024.
- **Pre-signed URL:** Amazon's name for a special web address that lets someone upload without having their own credentials.
- **Precomputing:** Working something out ahead of time.
- **Prefix:** The beginning of a word.
- **Premiere:** A video's first public showing.
- **Presence:** The word for who's online.
- **Primary key:** A column where every row has a different value, so one number can only mean one row.
- **Prime meridian:** The line through Greenwich, in London, where longitude is zero. People had to agree on one.
- **Priority queue:** A line where the most urgent thing goes next, instead of the oldest thing.
- **Private IP:** An address that only works between machines on the same private network.
- **Process:** A program that's running on a machine.
- **Producer / consumer:** Producers (publishers) create messages, and consumers (subscribers) read them and do the work.
- **Projection:** A rule that says, this spot on the ball goes to this spot on the paper.
- **Prompt:** The whole thing that you send in.
- **Prompt caching:** Keeping the model's notes from reading a prompt, and reusing them when a later request has the same beginning.
- **Protocol:** A set of rules two sides agree on, like taking turns on a phone call.
- **Proximity service:** A service that finds what's close to you.
- **Public IP:** An address anyone on the internet can reach.
- **Public key / private key:** The padlock and the key. The public key is fine for everybody to have. The private key never leaves your phone.
- **Publish and subscribe:** You say once that you want something, and from then on, every new update just shows up, like a newspaper subscription. Also: Publishing means sending something out, and subscribing means asking to receive it. People usually shorten it to pub-sub.
- **Pulsar:** An open source system that started at Yahoo. It keeps logs in a separate storage layer, so brokers don't need disks.
- **Push / pull:** Push: the broker sends messages as soon as they show up. Pull: the reader asks for them.
- **Push model / pull model:** Other names for fan-out on write and fan-out on read. They have nothing to do with push notifications.
- **Push notification:** A little message that pops up on your screen from an app, even when the app is closed.
- **Put / get:** The 2 operations. Put saves a value under a key, and get gives you the value for a key.

## Q

- **QPS:** Queries per second. How many operations, like sending a message, happen in each second.
- **Quadkey:** A kind of address where each digit says which of the 4 you went into. Also: These same tiles, written as one string of digits.
- **Quadtree:** A tree where each square has 4 children, and you only keep cutting where it's crowded. Quad just means four.
- **Query:** What someone typed into a search box.
- **Quintillion:** A billion billions.
- **Quorum:** The rule some clubs have, that a vote only counts if enough members show up. Here, enough servers have to answer.

## R

- **R:** How many servers have to answer before a read is finished.
- **R-tree:** A tree of boxes around places. Instead of cutting up the map ahead of time, the boxes follow the data.
- **RabbitMQ:** A very popular open source message broker. It exists so you don't have to build all that delivering and retrying yourself.
- **Race condition:** The result depends on the timing of two things happening at the same moment.
- **Rack:** A tall cabinet of servers in a data center. If its power fails, everything in it goes together.
- **Radio:** The part of the phone that talks to the network.
- **Radius:** How far you're searching from the middle.
- **Raft:** A well known set of rules for a group of machines to agree on one leader and one history.
- **RAID:** Redundant array of independent disks. A way to make several disks act like one, usually so one can die without losing anything.
- **RAM:** Random access memory. The computer's short-term memory.
- **Ranges:** Giving each server a block of numbers to count through on its own, instead of asking for one number at a time.
- **Ransomware:** A kind of attack that scrambles your files and asks for money.
- **Raster image:** An image stored as a grid of pixels. Raster just means a grid.
- **Rate limiter:** Decides how many requests a client is allowed to send over a certain period of time. Extra requests get blocked.
- **Read operations:** Anything that only looks at data.
- **Read-heavy:** Way more reads than writes.
- **Rebalancing:** Working out who reads what.
- **Recursion:** When a program does the same thing to each smaller piece, again and again.
- **Red flag:** Something you do that makes the interviewer worried about hiring you.
- **Redirect:** Like a note on a shop door saying we've moved. The server doesn't fetch the page, it tells the browser where to go.
- **Redis:** An in-memory database that's very fast. Also: Remote Dictionary Server. A key-value store in memory that you can run yourself, or get as a managed service from cloud providers such as AWS and Microsoft.
- **Redundancy:** Having multiple copies of a resource. Having the spare tire.
- **Refill rate:** How fast tokens come back.
- **Relational database (RDBMS):** Stores data in tables and rows, like a spreadsheet. Also called a SQL database.
- **Relative link:** A link that isn't a full address, like saying the room down the hall. It only makes sense if you know which building you're in.
- **Release:** Putting a new version of our code on the servers.
- **Remainder:** What's left over after dividing.
- **Replay:** Moving your bookmark back and reading those messages again.
- **Replica:** A copy of the data. The copy that takes writes is the leader, and the others are followers.
- **Request body:** The part of a request that carries what you're sending.
- **Requirement:** Something our design has to do.
- **Resolution:** How many dots a picture has. 1080p is 1,080 rows, each 1,920 dots wide. 4K has about 4 times the dots.
- **REST:** A popular style of building web APIs, where each thing has its own address and you use a few standard words.
- **Resumable upload:** After an interruption, the client asks how many bytes have arrived, and continues from the next one.
- **Retention:** How many of your users keep coming back.
- **Retrieval (RAG):** Fetching what's relevant before you ask. RAG stands for retrieval augmented generation.
- **Retry storm:** Everything that failed tries again at once, so a struggling service gets way more traffic than usual.
- **Retry topic:** A separate log for things to try again later, so that the main line keeps moving.
- **Retry-After:** A standard, optional header that tells the client how long to wait before trying again.
- **Reverse chronological:** The formal name for newest first.
- **Reverse geocoding:** Going from a dot to words, like showing you what street you're on.
- **Road segment:** A piece of a road, usually from one junction to the next.
- **robots.txt:** A small file where a website says what it wants crawlers to do. It's voluntary.
- **RocketMQ:** An open source system that came out of Alibaba's online stores, and that also keeps messages in logs.
- **Rolling checksum:** What rsync uses. A checksum is just a short number used to check data.
- **Rolling release:** Restarting a few servers at a time.
- **Root:** The one number at the top of the tree.
- **Round:** One time through.
- **Round robin:** Taking turns: the first message goes in volume 0, the next in volume 1, and so on.
- **Round trip:** A trip across the network there and back. It has a cost that doesn't care how small your message is.
- **Routing tiles:** Squares that the road network is cut into, in 3 sets from every street to only highways.
- **rsync:** A free tool that exists to update a file on another machine by only sending what's different.

## S

- **S2:** Google's library for working with data on the real, round planet.
- **Salt:** The extra bit you add to the input before hashing again, like the number 1.
- **Sampling:** Only writing down some of the data, picked at random, like 1 search in 10.
- **Scanning:** Trying code after code.
- **Scheduler:** A small program that watches the graphs, and puts a task in line when it's free to start.
- **Schema:** The tables and columns. Each shard has the same schema, with different data.
- **Scope:** What's included in the thing we're building, and what's not.
- **ScyllaDB:** A database built to work like Cassandra.
- **Search index:** The collection of pages a search engine can search through.
- **Search service:** A separate part of our system whose only job is finding books.
- **Secret key:** Like a password that one program uses to prove who it is to another program.
- **Seed URLs:** A few starting addresses, called seeds because everything else grows from them.
- **Segment:** One of the smaller files that a volume is cut into.
- **Selector:** Takes links out of the priority lines, picking from high most often.
- **Sentinel:** A Redis tool that watches its servers and can promote a copy automatically.
- **Sequence number:** The count section of the ID. It goes back to 0 every new millisecond.
- **Sequential / random:** Reading or writing in one straight line, or jumping around.
- **Serialization:** Converting something, like an object in your code, into a format that can be stored or sent, like JSON. Deserialization is the opposite.
- **Server:** A computer, or a program on one, that provides services, data or resources to other computers.
- **Server-sent events:** Only the server talks, over a normal HTTP connection.
- **Server-side rendering:** The website's own server builds the full page before sending it.
- **Service credits:** Money off your future bills.
- **Service discovery:** A way of finding out which servers exist, and which one to use.
- **Service provider:** The company that runs and offers a service, like AWS, Google Cloud or Microsoft Azure.
- **Session registry:** Our front desk: one simple lookup of which chat server each person is on.
- **Set:** A hash table for the question, have I seen this? We only care whether the hook has been used.
- **SHA-256:** A long and strong hash, which Dropbox's posts say it uses.
- **Shard exhaustion:** When some shards fill up much faster than others.
- **Sharding:** Horizontal scaling for databases. Splitting a large database into smaller parts called shards.
- **Sharding key:** One or more columns that determine how data is distributed. Also called a partition key.
- **Share groups:** A Kafka feature where members of a group can share one partition, message by message, like a mailbox.
- **Shared access signature:** Microsoft's name for its version of a pre-signed URL.
- **Shifting:** Sliding bits to the left to leave room, like adding 3 zeros after 0930. Each place is the same as doubling the number.
- **Shortest path:** In this chapter, the smallest total time.
- **Signal Protocol:** A published design for this kind of encryption. WhatsApp's paper says it's built on it.
- **Signed cookie:** A cookie is a small note your browser keeps, and sends with every request to that site. A signed one can cover all of a video's pieces.
- **Signed link:** A special address that can't be changed without us noticing, and that expires soon.
- **Silent push:** A kind of push with nothing to show, which wakes your app up for a moment.
- **SimHash:** A way of making a fingerprint where similar pages get almost the same number, so you can spot near copies.
- **Single point of failure:** One part of a system that takes the whole system down when it fails.
- **SLA:** Service level agreement. A formal contract that says how much uptime a customer should expect, and what happens if the provider misses that.
- **Sliding window counter:** Keeps counts for the current and previous minutes, and estimates how many requests are in the last 60 seconds.
- **Sliding window log:** Keeps a log of timestamps for each customer, and looks back at exactly the last 60 seconds on every request.
- **Sloppy quorum:** Counts the first healthy servers, even if they aren't the usual ones.
- **SMS:** Short message service. A text message, sent over the phone network to a phone number.
- **Snapshot:** A picture of everything at one moment, like a saved copy of a trie.
- **Snowflake:** An ID layout built at Twitter: sections for time, place and a count, in 64 bits.
- **Soft limit:** A limit that can be passed for a short time.
- **Soft real time:** We try to be quick, and nothing is broken if we're a few seconds behind.
- **Solid state drive:** A drive with no moving arm, where the gap between sequential and random is a lot smaller.
- **Sorted set:** Like a set, so there are no duplicates, except each item has a number called a score, and everything stays in order of that number.
- **Spam:** Pages stuffed with popular words to fool search engines.
- **SPF, DKIM and DMARC:** Three checks that prove an email really came from your domain, so nobody can pretend to be you.
- **Spider trap:** A path of pages a crawler can follow forever. A crawler is sometimes called a spider, and some people build these on purpose.
- **SQL:** The language you use to talk to a relational database.
- **SSTable:** Sorted string table. A box on disk that's sorted and never changed.
- **Stack:** A pile of plates. The last one on is the first one off.
- **Staging:** A practice copy of a system.
- **Stale data:** Data that's out of date.
- **Standard deviation:** A measure of how spread out numbers are around their average.
- **Standby:** A copy that's kept up to date and ready to take over.
- **State / session data:** Information a server remembers about a user, like that you're logged in.
- **Stateful server:** Remembers client data from one request to the next.
- **Stateless server:** Keeps no state information.
- **Static content:** Files that are the same for everyone, like images, videos, CSS and JavaScript.
- **Status code:** The number every answer from a web server starts with. The first digit tells you what kind of answer it is.
- **Sticky sessions:** The load balancer sends every request from one client to the same server.
- **Stream:** Data that keeps arriving and doesn't really have an end.
- **Streaming:** Sending the answer in pieces as it's made.
- **Strict quorum:** Only counts the usual servers, like A, B and C.
- **Strong consistency:** Once a change is finished, every read, from anyone, gets the new data.
- **Subnet:** A range of addresses that defines which network machines belong to.
- **Surge pricing:** The higher price when there are too many riders and not enough cars.
- **Sync:** Keeping copies in different places the same.
- **Synchronous:** The sender waits until the receiver is done. Like calling a friend.

## T

- **TCP:** Gets data across the internet reliably, with all the pieces, in the right order.
- **Template:** A message with blanks in it, filled in at the last moment.
- **Temporal:** An open source platform that exists so that a long-running job can keep its progress when something fails.
- **Terabyte (TB):** 1,024 gigabytes. Round it to a trillion bytes.
- **Theorem:** A rule that somebody has proven.
- **Third party:** Someone outside of our company doing part of our job.
- **Thread:** One worker inside a program, doing one thing at a time.
- **Throttling:** Limiting someone's requests. If a user is throttled, the rate limiter stepped in.
- **Throughput:** How much gets through in a second.
- **Thumbnail:** A tiny, blurry version of a picture.
- **Thundering herd:** Adele's post expires from the cache, thousands of people ask for it, and they all go to the database at once. A common fix is to let one request go get it, while everyone else waits a moment. You probably won't get asked this.
- **Ticket server:** A small database with a counter, whose only job is to hand out numbers. Like the ticket machine at a deli counter.
- **Tier:** One of the levels that companies set their limits at.
- **Tiered storage:** Where finished segments can go to something like S3, while the newest stay on local disks.
- **Time to first token:** How long until the first token shows up.
- **Time wheel:** A common way to track a lot of timers. One bucket per second, and a hand moves around and empties each one.
- **Timeout:** How long we're willing to wait before giving up.
- **Timestamp:** A record of the exact time that something happened.
- **TLS:** The technology underneath HTTPS. SSL is the old name, and its last version was officially ruled out in 2015, so please say TLS.
- **Token:** A small piece of text. Sometimes a whole word, sometimes part of a word, and sometimes only a comma.
- **Token bucket:** Each request pays with a token from a bucket that refills at a steady speed. Empty means rejected.
- **Tombstone:** A small marker that says this was deleted.
- **Top K:** Give me the K most popular things. K is just a number, and for us it's 5.
- **Topic:** A name for one stream of messages, like one book.
- **TPU:** Tensor processing unit. Google's custom chip for machine learning.
- **Tracking parameters:** Small notes a link carries after the question mark, so a company knows where you came from.
- **Tracking pixel:** A tiny invisible image in an email. When your mail app loads it, the sender finds out.
- **Tradeoff:** What you give up in order to get something.
- **Trading space for time:** We spend memory, which we can buy, and we get back time.
- **Training:** Teaching the model by practicing on a huge amount of text. It's a giant project that happens before you ever meet the model.
- **Transactions (Kafka):** A program reads from some topics, writes to others and moves its bookmark, all as one step that either all happens or doesn't.
- **Transcoding:** Turning one encoded video into a different one: a different codec, resolution or bitrate.
- **Transfer Acceleration:** An Amazon feature where data goes in at a nearby CDN location, then travels over a better path to storage. Kind of a CDN in reverse.
- **Traveling salesman problem:** Finding which order a vehicle with a lot of stops should go in.
- **Tree:** A shape of fingerprints that branches out, even though it's upside down. Also: Things hang off each other, with the middle at the top, what comes before it to the left and what comes after it to the right, so each step cuts what's left in half.
- **Triage:** The desk at the front of an emergency room, where a nurse decides how urgent you are.
- **Trie:** A tree made out of letters, where the path from the root spells out what you've typed. Spelled T R I E.
- **Trilateration:** Finding someone from their distance to 3 different spots.
- **TTL:** Time to live. How long a file should stay cached.
- **Tunable consistency:** Being able to tune how in sync the copies are.
- **Turn:** One question and its answer.
- **tus:** An open protocol that exists so that any app can have resumable uploads over normal HTTP, without building its own.
- **Twilio:** A company that businesses pay to send texts for them.
- **Two-dimensional:** You need 2 numbers to say where something is, like a row and a column to find a seat.
- **Two-way sharing:** Friends who agree to see each other. In one-way sharing, I can see you and you can't see me.

## U

- **Unicode:** The standard that gives a number to the characters of all the world's writing systems, with room for over a million.
- **Uniqueness rule:** Something you tell the database about a column: no 2 rows can ever have the same value here.
- **Unix time:** Computers usually count time from January 1, 1970.
- **Unstructured data:** Data that doesn't fit neatly into tables.
- **Uptime:** The time that the system is up and working.
- **URL:** Uniform resource locator. The full address of a page on the internet.
- **URL frontier:** The crawler's to-do list. It holds every link we want to visit and haven't visited yet.
- **URL Seen:** The box that asks: have we already got this address?
- **Use case:** What something is actually going to be used for.
- **UTC:** One clock that the whole world agrees on, so that time zones don't confuse anything.
- **UTF-8:** The usual way of storing Unicode, taking between 1 and 4 bytes for each character.
- **UUID:** Universally unique identifier. A 128-bit number so big and so random that you can make one whenever you want.

## V

- **Vector clock:** A small list of servers and write counts that travels with each version. Vector means a list of numbers, and it tells you the order things happened in without looking at the time.
- **Vector tile:** A tile sent as a list of what's in it. Vector means it's made of lines and shapes, not pixels.
- **Versioning:** Adding a version number to a file's address, so the CDN treats it as new.
- **Viewport:** The part of the map that's on your screen right now.
- **Virtual node:** One more place on the ring for a real machine. It isn't a real machine, and it isn't a copy of any data.
- **Visibility timeout:** How Amazon's ready-made queue service, SQS, hides a message from everyone else for a while. It shows up again if the worker didn't finish.
- **vLLM:** An open source program for running these models, which started at UC Berkeley, so you don't have to build all of this yourself.
- **Volatile:** Lost when a server restarts, as data in memory is.
- **VP9:** A newer codec from Google, free to use.

## W

- **W:** How many servers have to say got it before a write is finished.
- **Watermark:** A mark inside the video that says whose it is: a logo you see, or a hidden pattern that's different for each customer.
- **Waze:** A navigation app that's built around drivers reporting what they see.
- **Weak consistency:** You might see new data or old data, and the system doesn't tell you when that changes.
- **Web crawler:** A program that goes and gets pages from around the web: download, pull out the links, add them to the list, and repeat.
- **Web Mercator:** The version nearly every web map uses. It's Mercator with a small simplification that treats the Earth as a perfect ball.
- **Web tier / data tier:** The layer handling web and mobile traffic, and the layer holding the database.
- **WebRTC:** Web real-time communication. It exists so that browsers and apps can send live sound and video directly to each other, often without a server in the middle.
- **WebSocket:** A protocol built so that either side can talk whenever they want, over a connection that stays open.
- **Weight:** The number on an arrow. Here, how many minutes we expect that road to take.
- **Wide-column store:** A database where one key can hold many rows, kept in sorted order.
- **Widevine / FairPlay / PlayReady:** The DRM systems from Google, Apple and Microsoft. To reach every device, you often need more than one.
- **Window:** The stretch of time that we're counting in.
- **Worker:** A program that takes jobs from a queue and does them.
- **Write operations:** Anything that changes data, like inserts, updates and deletes.

## Y

- **YAML:** A text format that's an easy way to write settings so that people can read them.

## Z

- **Zanzibar:** A system Google published in 2019, so that its products can share one way of storing and checking these lists. You probably won't get asked this.
- **Zero copy:** Telling the operating system to send bytes straight from the page cache to the network, so our program doesn't touch them. It can't be used when the connection's encrypted with SSL.
- **Zipf:** A common pattern where number 2 is half as popular as number 1, number 3 gets a third, and so on.
- **ZooKeeper:** A small and very reliable place where machines can agree on things. You don't need to know how it works.
- **Zoom level:** One copy of the whole map, at one distance from far away to very close.

---

From the course **[System Design: Zero to Interview Hero](https://www.udemy.com/course/system-design-zero-to-hero/?referralCode=183D59A1EBE9E71D26FF)** by Nata Vacheishvili.
