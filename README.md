# Relevancy-Review
PY script analysing TXT output for relevance to a RISEN prompt

The script is utilising the following workflow to analyse simple text documents for their relevance to a RISEN prompt: 

1. Taking into consideration RISEN framework and instructions by the user in that format. 
2. Taking into consideration temperature configurations of relevancy, this is provided in .CSV template. 
3. Intake from a folder where .TXT files resides for analysis. 
4. Establishing API connection to OpenAI 
5. Once the analysis of the .TXT files is completed a result is outputted in the form of CSV.   
6. Output of a CSV file based on the relevancy of the RISEN prompt, in the .CSV file you need to include the following columns - Document name, Relevancy score and Annotation/Comments (why this document is relevant to the RISEN prompt).
7. The PY code is then run in Visual Studio Code locally. 
8. API token to OpenAI is not provided. 
