# Dyadic Default Plugins

[All Plugins](../README.md) · [Skills](https://git.lley.cat/r/1a151e58-468a-45f1-a028-92c95690ad68?ref=store) · [Agents](https://git.lley.cat/r/dadd28be-7d91-432f-beb0-00d285e8f02b?ref=store) · [Plugins](https://git.lley.cat/r/ae86ea71-cb4d-4fc5-9ec1-803f8f303989?ref=store)

The complete 40-item built-in catalog at the pinned source revision. Names, descriptions and switch IDs below come from the manifests.

| Plugin | Purpose | Runtime switch |
| --- | --- | --- |
| [Anime & Manga](anime/README.md) | AniList titles, airing status and adaptations. Commercial permission required; no downloads. | `anime.*` |
| [Barcodes & QR](barcodes/README.md) | Scan barcodes locally and create QR or barcode files in your Workspace. | `barcodes.*` |
| [AI Benchmarks](benchmarks/README.md) | Compare published model benchmark evidence from OpenRouter and BenchLM, with source dates and uncertainty. | `benchmarks.*` |
| [Books & Comics](books/README.md) | Open Library and Google Books bibliographic search and ISBN lookup; keep editions distinct. | `books.*` |
| [Browser](browser/README.md) | Use a real web browser: open pages, click, fill in forms and download files. | `browser.*` |
| [Code Sandbox](code/README.md) | Files and folders in your workspace, and an network-isolated sandbox to write and run code. | `workspace.*` |
| [Your Computer](computer/README.md) | Let Iris run commands on your own computer through the Dyadic Runner and send you files from it: build and start Docker containers, deploy, use your tools. Pair it with one command and a code; it asks you first unless you allow it. | `machine.*` |
| [Conversions](conversions/README.md) | Dated currency reference rates and local physical-unit conversions. | `convert.*` |
| [Database](database/README.md) | Explore and query your PostgreSQL, MySQL and SQLite databases. Reads only, unless you allow changes, and every change asks you first. | `database.*` |
| [Documents](documents/README.md) | Read, make and edit Word, PDF, Markdown and text files. | `documents.*` |
| [Flight Observations](flights/README.md) | FlyItalyADSB aircraft observations near coordinates or by callsign, registration or ICAO hex. Community receiver coverage, not schedules or fares. | `flights.*` |
| [Food & Nutrition](food/README.md) | Look up food labels, barcodes, nutrients and recipes. | `food.*` |
| [Forensics](forensics/README.md) | Investigate public sources, organize private cases and inspect evidence, relationships and timelines. | `forensics.*` |
| [Game Catalog](game-catalog/README.md) | CheapShark deals and Steam metadata, requirements and regional prices. Separate from games to play. | `games.catalog` |
| [GitHub](github/README.md) | Read and change your GitHub repositories: push code from your Workspace, create repositories and branches, open and merge pull requests, and manage issues. Every change asks you first. | `github.*` |
| [Google Workspace](google/README.md) | Drive, Gmail, Calendar, Docs and Sheets as your Google account, at the level you allow each. Sending email, calendar changes and edits ask you first. | `google.*` |
| [Health & Exercise](health/README.md) | Public RxNorm drug references, FDA drug recalls and attributed wger exercise browsing. Medical research reuses Science. | `health.*` |
| [History](history/README.md) | Wikipedia and Wikidata historical discovery with sourced identifiers and article links. | `history.*` |
| [Holidays](holidays/README.md) | Nager.Date and OpenHolidays public, school and regional holiday calendars. | `holidays.*` |
| [HTTP Request](http-request/README.md) | Call web APIs, REST and GraphQL, with the sign-ins you save. Every change asks you first. | `http.request` |
| [Image Analysis](image-analysis/README.md) | Look at an image and describe it, or answer a question about it. | `vision.describe_image` |
| [Image Generation](image-generation/README.md) | Create images from a description or a reference upload. | `image.generate` |
| [Knowledge Search](knowledge-search/README.md) | Search your files, chats, projects and memory, and cite them. | `knowledge.search` |
| [Memory](memory/README.md) | Learn lasting preferences, remember what you ask, and find, change or forget it later. | `memory.*` |
| [Movies & Television](movies/README.md) | TVMaze show discovery, cast, episode guides and schedules; films through existing Reference. | `movies.*` |
| [Music](music/README.md) | MusicBrainz artist, release and recording metadata. Hosted permission or private evaluation access required. | `music.*` |
| [OCR](ocr/README.md) | Read the text in scans, screenshots, receipts and photos of documents. | `vision.read_text` |
| [Web Page Reader](read-web-pages/README.md) | Open and read a link you share. | `data.web_fetch` |
| [Scheduler](scheduler/README.md) | Have an agent do something on a schedule, like every Tuesday or every hour, and tell you when something happens. | `schedule.*` |
| [Science & Research](science/README.md) | Search Crossref and OpenAlex publications and look up DOI metadata. | `science.*` |
| [Scripture](scripture/README.md) | Commercially reusable Bible translations, books and verse-preserving chapter reads through Free Use Bible API. | `religion.*` |
| [Space](space/README.md) | Find NASA media, astronomy pictures and upcoming space launches. | `space.*` |
| [Speech](speech/README.md) | Read an answer or any text aloud as an audio file you can play. | `audio.speak` |
| [Sports](sports/README.md) | OpenLigaDB community leagues, match schedules, results and standings. Primarily European football coverage. | `sports.*` |
| [Spreadsheets](spreadsheets/README.md) | Make and edit Excel and CSV files, with formulas, tables and charts. | `spreadsheets.*` |
| [Transcription](transcription/README.md) | Write down what an audio file you attach says. | `audio.transcribe` |
| [Travel](travel/README.md) | Wikivoyage travel guides connected to existing Overture places, Valhalla routes and weather. | `travel.*` |
| [Vehicles](vehicles/README.md) | NHTSA VIN decoding, recalls and FuelEconomy.gov vehicle specifications and estimates. | `vehicles.*` |
| [Weather](weather/README.md) | Forecasts, official alerts and specialized weather data, with source attribution. | `weather.*` |
| [Web Search](web-search/README.md) | Search the web and cite sources before answering. | `data.web_search` |
