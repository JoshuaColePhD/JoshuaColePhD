# Joshua Cole, PhD

**Applied AI engineer · Grounded LLM products · Evaluation · Edtech**

I build applied AI products and the checks that keep them honest: retrieval that cites the right source, structured outputs that are validated before they are saved, and regression tests that catch failures before users do. I bring a PhD in Educational Leadership, ten years in education, and contract AI evaluation work since 2023, so I build edtech tools with a teacher's eye for what counts as a correct answer.

**Stack:** Python · FastAPI · TypeScript · React · Swift/SwiftUI · Postgres/Supabase · OpenAI structured outputs · RAG (keyword + semantic retrieval) · pytest · XCTest · GitHub Actions · R · SQL

Open to applied AI engineering, AI evaluation, and edtech engineering roles. [LinkedIn](https://www.linkedin.com/in/joshuacolephd/) · [Email](mailto:joshuacolephd@gmail.com)

## Featured projects

### FlexEd Academy: grounded AI lesson planning for teachers

Turns a weekly teaching request into a standards-grounded lesson plan and an editable Word document. I demonstrated it to teachers, and the live read-only demo is public.

- **Debugging:** I traced a bug where retrieval returned standards for the wrong course, added course filters to retrieval, and wrote regression tests for cross-course citations.
- **Retrieval regression gate:** the expected standard appears in the top five results for **61/61** recorded cases (recall@5).
- **Citation audits:** every cited standard is checked against retrieved sources and flagged if it was not retrieved, borrowed from another scope, or invented.
- **Document export:** recoverable generation and Word-export jobs, so a dropped connection does not discard finished work.

**[Watch the demo GIF](https://raw.githubusercontent.com/JoshuaColePhD/FlexedAcademy-Showcase/main/media/flexed-current-demo.gif)** · [Showcase and case study](https://github.com/JoshuaColePhD/FlexedAcademy-Showcase) · [Live demo](https://flexedacademy.com)

### CameraCue Studio: a Mac teleprompter that follows your voice

Native Swift app that keeps your place in the script through pauses, skips, and restarts using on-device speech tracking. A held-out replay of 6,408 simulated recognizer callbacks kept the reader within two script tokens of the speaker **99.44%** of the time, and the app has 46 XCTest files.

**[Watch the demo GIF](https://raw.githubusercontent.com/JoshuaColePhD/CameraCue-Showcase/main/media/studio-demo.gif)** · [CameraCue showcase](https://github.com/JoshuaColePhD/CameraCue-Showcase)

### Nalu: dictation into any Mac app (in development)

Hold Fn, speak, and release. Nalu transcribes on the Mac, optionally cleans up the text with an LLM, and checks that numbers and negation survived before inserting the text. I compare prompt changes on matched inputs; I held one update that passed 8/8 targeted checks but not the broader test run.

**[Watch the demo GIF](https://raw.githubusercontent.com/JoshuaColePhD/Nalu-Portfolio/main/media/nalu-showcase-preview.gif)** · [Nalu portfolio](https://github.com/JoshuaColePhD/Nalu-Portfolio)

### DraftLoop: testing AI essay scoring

A writing-coach prototype for AP English Language students. Requiring structured fields and a larger token limit brought complete model responses from 0/3 to 3/3, while exact score agreement stayed at 0%. That separated a response-format bug from a real scoring-reliability problem.

**[Watch the demo GIF](https://raw.githubusercontent.com/JoshuaColePhD/DraftLoop-Showcase/main/demo/assets/current-coach-demo.gif)** · [Case study and results](https://github.com/JoshuaColePhD/DraftLoop-Showcase)

*Results are scoped to the recorded evaluation sets described in each showcase. Application source for these products is private; showcases contain evidence, not source.*

## Supporting work

[CueFrame (Mac recorder, open source)](https://github.com/JoshuaColePhD/CueFrame) · [Argument Architect (edtech)](https://github.com/JoshuaColePhD/Argument_Architect) · [SQL and transportation analytics](https://github.com/JoshuaColePhD/BigQuery_Transportation_Analytics) · [Python purchase prediction](https://github.com/JoshuaColePhD/Customer_Purchase_Prediction) · [R survival analysis](https://github.com/JoshuaColePhD/HR_Attrition_and_Survival_Analysis) · [Electricity forecasting](https://github.com/JoshuaColePhD/Household_Electric_Consumption_Analysis)
