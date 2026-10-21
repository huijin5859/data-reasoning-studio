<p><img src="assets/drs-fullname-light.svg" alt="DRS — Data Reasoning Studio" width="320"></p>

# DRS — Data Reasoning Studio

Data Reasoning Studio (DRS) is a web-based research prototype that helps K-12 students reason with messy, authentic scientific data. Students work through four reasoning processes: Extraction, Identification, Interpretation, and Storytelling. Along the way, an AI thinking partner asks probing questions, surfaces misconceptions, and scaffolds their reasoning. It does not give them the answers.

DRS is in early development. It is being built with teachers and families, with support from the National Science Foundation (Award No. 2627588).

# Try an Example

[▶ Open Data Reasoning Studio](https://huijin5859.github.io/data-reasoning-studio/): no account or installation needed. Currently, live AI responses are available only to Georgia Southern University accounts. 

Try it in 10 minutes: the Wolves and Moose task 

Click the first dataset, Isle Royale wolves and moose. On the right, under Saved tasks, find the example task Wolves and Moose and click Open.

The quickest way to see DRS is to work through the built-in example task, Wolves and Moose. It uses long-term data from the Isle Royale Wolf-Moose Project conducted by scientists at Michigan Tech.

## See it as a student

Open Data Reasoning Studio. It opens on the Datasets page.
Click the first dataset, Isle Royale wolves and moose. This takes you to the Teacher view.
On the right, under Saved tasks, find the example task Wolves and Moose and click Open. 

The task opens in the student view at the first stage, Extraction. Work through the four stage tabs in order: Extraction → Identification → Interpretation → Storytelling.
When a question asks for a written answer, type your answer, then click Ask your thinking partner. The partner responds to what you wrote and pushes your reasoning further. Currently, this function is only available to Georgia Southern accounts.

## See how a teacher builds it

Go back to Teacher, and under Saved tasks click Edit on Wolves and Moose.
Open each section to see how the task is set up: the background, the questions for each of the four stages, the thinking partner's role, and the exact wording the thinking partner is given.
Click Try it as a student at any point to preview your changes.

To build your own task, click Start a new task, or pick a dataset from the Datasets tab. The Vocabulary tab defines the data terms students meet along the way.

Note: Currently, DRS saves nothing to follow IRB requirements. Your work and any tasks you create disappear when you close the tab. Download your data story before you leave.

# Two Versions
There are two versions. Currently, neither of them saves anything, per IRB requirement. When you close the tab, your work is gone, so download your data stories before you leave.

[Open Data Reasoning Studio](https://huijin5859.github.io/data-reasoning-studio/) — the public version. No account needed. You can move through all four stages, explore the built-in datasets, build and annotate charts, and write responses. 

[Open the version with live AI](https://claude.ai/artifact/AJNZTzCdFzjwTprCTyLqc1?sk=M_7HXs6Eg0eTN5dgFxo0bw) — the same tool, with real AI feedback that responds to what you actually wrote. Currently, the AI function is only accessible to Georgia Southern accounts per GS regulation.

## What Students Do

Extraction — What did the scientists measure, and how well? Students separate observations, variables and values, first on a picture-based extraction web and then in a table.

Identification — What patterns and surprises are in the data? Students build distributions, compare them side by side, and turn one sideways to make a scatterplot. Signal, noise, trends and anomalies.

Interpretation — What could explain what you found? Students annotate their charts — marking points, drawing reference lines, shading regions — and write explanations that connect the data to known science.

Storytelling — What is the story, and who should hear it? Students connect charts and notes on a canvas to build an argument, then publish or download it.

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

Hui Jin, Georgia Southern University (Principal Investigator)

Andrew Allen, Georgia Southern University (Co-Principal Investigator)

Vijayalakshmi Ramasamy, Georgia Southern University (Co-Principal Investigator)

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
