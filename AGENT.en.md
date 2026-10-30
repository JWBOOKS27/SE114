# Task 1
## Tasks
1. Perform bitext alignment at the sentence level on the following pair of files @tea.zh.txt (source) and @tea.en.txt (target). Use the LLM to perform the alignment instead of a Python script. Place each aligned segment pair on the same line, with a tab character separating the source and target segments. If there’s no matching target sentence(s), just leave the target string empty. Name the aligned text "tea.zh-en.txt".
2. Extract a glossary of Taiwan-specific cultural terms. Include as many entries as possible, but no fewer than 30. Place each zh-en glossary pair on the same line, with the two parts separated by a tab character. Name the glossary file "tea.glossary.zh-en.txt".

# Task 2
## Tasks
1. Translate the source text @Condor_Ch04.zh.txt, which is from a modern Chinese martial art (wuxia) novel, into idiomatic English, using the glossary of proper names and special terms from the file @Condor_glossary.txt .
2. Name the English translation "Condor_Ch04.en.txt".


# Task 3
## Tasks
Extract Chinese text from @南宋抗金.pdf and save the output to a Markdown file with the same file name and the file extension .md please. Ignore page boundaries and numbers and reconstitute broken sentences and paragraphs into complete units. Create Markdown tables if the PDF pages contain tables. Place all footnotes in a separate section at the end of the Markdown file, with each footnote on its separate line and add a blank line between footnotes.

# Task 4
NAER 外國地名譯名 → DSL

# Tasks
1. Downloads the 國家教育研究院-外國地名譯名 dataset from
https://terms.naer.edu.tw/media/terms_data/1/外國地名譯名壓縮檔_VrsZ2AD.zip

2. Convert the ODS spreadsheet files contained in the above ZIP archive into DSL format (Abbyy Lingvo DSL dictionary).

3. Produce a single .dsl file called 外國地名譯名.dsl with the encoding UTF-16 LE. No dictzip compression necessary.

4. Keep track of the time elapsed of the entire job.
