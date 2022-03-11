# Comparing Tests and Implementations Programmatically

<br>

## **How I Compared My Test Results to the Professor's Test Results**
- ran the professor's markdown parse code against all of the test files in the professor's `markdown-parse` repository with `bash script.sh` and stored it locally in `results.txt` in the professor's repository
- ran my markdown parse code against all of the test files in the professor's `markdown-parse` repository with `bash script.sh` and stored it locally in `results.txt` in my own repository
- used the `diff` command with the file paths to my `results.txt` and the professor's `results.txt` to compare the outputs of each test and return any differences
- printed out names of test file that the output corresponds to so when differences between the two `results.txt` are found, I know exactly which one
<br>

![Diff Command](DiffCommand.png)

---

<br>

## **Test #1**
<br>

![MDTest1](MDTest1.png)
- My Output: `[]`
- Professor's Output: `[\uri]`
- Expected Output: `[\uri]`

My markdown-parse implementation was wrong.
<br> <br>

### Input From Test File: *`[link](/uri)`*
<br>