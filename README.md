<p><img src="assets/drs-fullname-light.svg" alt="DRS — Data Reasoning Studio" width="320"></p>

# DRS — Data Reasoning Studio

A research prototype for helping students reason with messy, authentic scientific data through four reasoning processes: **Extraction, Identification, Interpretation, and Storytelling.**

DRS is designed for K-12 science classrooms, where students work directly with authentic research data while an AI partner supports their reasoning, surfaces misconceptions, and asks probing questions. DRS is in early development and is being built as a community-led project with teachers and families.

## Try it

There are two versions. Neither of them saves anything. When you close the tab, your work is gone, so download your data stories before you leave.

[Open Data Reasoning Studio](https://huijin5859.github.io/data-reasoning-studio/) — the public version. No account needed. You can move through all four stages, explore the built-in datasets, build and annotate charts, and write responses. The AI feedback here is a set of pre-written example responses, not live AI.

[Open the version with live AI](https://claude.ai/artifact/AJNZTzCdFzjwTprCTyLqc1?sk=M_7HXs6Eg0eTN5dgFxo0bw) — the same tool, with real AI feedback that responds to what you actually wrote. This one requires a free Claude account; replies run on your own account, not the project's. Use this version if you want to judge the quality of the feedback.

## What Students Do

Extraction — What did the scientists measure, and how well? Students separate observations, variables and values, first on a picture-based extraction web and then in a table.

Identification — What patterns and surprises are in the data? Students build distributions, compare them side by side, and turn one sideways to make a scatterplot. Signal, noise, trends and anomalies.

Interpretation — What could explain what you found? Students annotate their charts — marking points, drawing reference lines, shading regions — and write explanations that connect the data to known science.

Storytelling — What is the story, and who should hear it? Students connect charts and notes on a canvas to build an argument, then publish or download it.

## For teachers

The tool includes a settings panel where you can rewrite the AI prompts in plain English. This is the part most worth experimenting with: you are better placed than we are to judge which wording actually helps your students. The AI does not score student work. It sees what students write and annotate, not who they are.

## Privacy and data

This version of DRS does not collect any data. It is deliberately built so that there is no student data to protect.

No accounts, no sign-in, no names. The app never asks who you are. 
Nothing is written to a database, to browser storage, or to cookies.
Nothing is transmitted to any server operated by this project. The page contains no fetch or XMLHttpRequest calls of its own.
Student work and teacher-authored tasks exist only in the browser's memory while the page is open, and are discarded when it closes.
Downloading a file is the only way anything leaves the page, and only the person using it can do that.

Two qualifications:

The page loads fonts from Google Fonts and two spreadsheet-reading libraries from cdnjs. Those providers therefore see the IP address of anyone who opens it, as they would for most web pages. 
On the full version hosted at claude.ai, AI replies are processed by Anthropic under that visitor's own account.  

Data collection will be added in a later version, as a deliberate design decision rather than a default.

## Project Team

**Creator and Project Lead:** Hui Jin, Georgia Southern University (Principal Investigator)

**Core Team:**
- Andrew Allen, Georgia Southern University (Co-Principal Investigator)
- Vijayalakshmi Ramasamy, Georgia Southern University (Co-Principal Investigator)

## Consultants

DRS is shaped by teachers and parents who serve as consultants to the project team. They review designs, test classroom materials, and make sure the tool meets the needs of students, teachers, and families.

**Teacher Consultants:**
- Patti Howell, Executive Director of Georgia Science Teachers Association, Americus Sumter High School South, Americus, GA
- Coco Anderson, Power School, Power, MT
- Melissa Goretskie, Power School, Power, MT

## Files

- `index.html` — the app. It is a single self-contained web page with no build step and no server code.
- `assets/` — logo (wordmark, full name, icon) and favicons

The four built-in datasets are included in the app and are publicly visible in this repository.

## Data Sources

- Isle Royale wolves and moose, Isle Royale Wolf-Moose Project: https://www.isleroyalewolf.org/
- EPA vehicle emissions test data, U.S. Environmental Protection Agency: https://www.epa.gov/compliance-and-fuel-economy-data/data-cars-used-testing-fuel-economy 
- Yellowstone wolves and elk: Cooper, D. J., & Hobbs, N. T. (2023). Twenty years of Salix height in response to experimental manipulation of browsing and water table, northern range of Yellowstone National Park [Dataset]. Dryad. https://doi.org/10.5061/dryad.sqv9s4n7n
- Pribilof Islands reindeer: Scheffer, V. B. (1951). The rise and fall of a reindeer herd. The Scientific Monthly, 73(6), 356–362. American Association for the Advancement of Science.

## Contributing

Contributions are welcome. All contributions are reviewed and accepted at the discretion of the project lead. Please open an issue to discuss proposed changes before submitting code.

## License

Licensing is being finalized. Please contact the project lead before reusing or redistributing any part of this project.


## Contact

Hui Jin, hjin@georgiasouthern.edu

## Acknowledgment

This material is based upon work supported by the National Science Foundation's Directorate for Technology, Innovation and Partnerships (TIP) under the Finders Foundry program, Grant No. 2627588. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.

We thank the students, families, and teachers whose participation and feedback help shape Data Reasoning Studio.
