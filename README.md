# addition-game-2023
Overview: Javascript-based Addition Game aimed for Elementary school students to practice their addition skills. The purpose of the output file is for teachers (or similar staff) to have a data-driven approach to how they evaluate the struggles of certain addition problems with a student.

Why: A friend of mine tutors special needs children and had a physical addition flashcard game of different two number, addition problems of integers 0-12 (e.g, "0+1", "2+11", etc.). The only issue is that when he would notice students would get stuck on certain types of problems (e.g., One student would always get stuck on problems that had a  "0" being added to another digit), then he was unable to note that sufficiently as it would ruin the flow of the student.

Problem: How can we sufficiently capture a student's ability to answer addition questions while also quantifying the attempts in a way that can be collected and analyzed without affecting a students results.

Solution: I built a javascript-based game that easily prompts a student with a series of randomly ordered addition questions (all summing up to the necessary pairings of the original game to avoid duplicates or uneven sampling). The game quantifies this by:
  - Logging each answer as incorrect/correct,
  - Logging time spent on each question,
  - Logging student's name for record purposes,
  - Ease-of-use by having large, easy-to-read text and compatibility for mobile, abd
  - Outputting a .csv result so that teachers/tutors can do quick statistical analysis on the results to see their current game progress and to pick out questions the student may have struggled on. Long-term, a teacher/student can aggregate different results into a master statistical analysis of a students addition progression over a semester or period.
