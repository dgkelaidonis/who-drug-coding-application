## About the application
The who-drug-coding-application constitutes the executable release of the internal private repository of the atcddd-classifier project, that implements the <b>Drug Coding</b> based on the [WHO ATC/DDD Index 2023](https://www.whocc.no/atc_ddd_index/). The application fully supports the search and classification based on ATC code or name, mapping all the corresponding classes between 1-6.

## How to run the application
Below there are the steps that should be followed in order to use the application
- <b>Step#1:</b> Download the `executable-release-*` zip file of the final release, from [here](https://github.com/dgkelaidonis/who-drug-coding-application/releases).
- <b>Step#2:</b> Unzip the file, and open the unzipped folder (i.e., the `executable-release-*`).
- <b>Step#3:</b> Use the sample excel file `input.xlsx` and put the ATC codes <b>OR</b> names, that you want to search into the respective column. 
- <b>Step#4:</b> `Save` the excel `input.xlsx` file and `close` it.
- <b>Step#5:</b> Open a `terminal` into the directory where the `input.xlsx` is. On Windows do this by `Shift + Right Mouse click` and select `Open Terminal here...`.
- <b>Step#6:</b> In the terminal run the command `./run.bat input.xlsx output.xlsx x/y/z`, where the x/y/z <b>must be the numbers of the ATC classes</b> you want to get for each code.
- <b>Step#7:</b> Wait few moments and as soon as the execution is completed, you should find the results into the excel file `output.xlsx`, that will be located in the same directory as the `input.xlsx`.
- Enjoy!
