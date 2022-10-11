# cs310-csv-json-fa21

  This project was assigned to me in the first half of my Software Engineering 1 course, CS310. The purpose of this assignment was to first, get a better understanding of GitHub, and learn how the website works, while also using Git to push our work to the repositories set up through GitHub. This project was intended to teach us how you can convert different forms of data from and to each other. In this respective project we are converting given data from a CSV file to a JSON file, and vice versa. 
  In this program, we were given the Main.java file, the Converter.java file, and the ConverterTest.java file to build off of. The Main file was used to set up the needed functions and procure the data while also getting it to where we needed it to be for the conversions to take place. I first obtained the CSV data by using the StringBuilder class to create the modifiable succession of characters so that they have a place to be stored. The BufferedReader then reads through the CSV file, separating the data in the file by line as it is read in so that it can be appended. This is then placed into a string for the future and the excess of the data that is not needed is trimmed off. I had to implement the same idea and exact approach into also getting and reading the JSON data. The Main file also will print out the Conversion results to the console by using a series of System.out.println features to print out the heading while also printing out the string data for both the JSON and CSV files. Before this can happen, the conversions need to be completed.
  The Conversion.java file deals with using the given JSON and Java Libraries to complete the needed conversions since we are not supposed to manually do any of the conversions. All of the string conversion needed to be left to the two data conversion libraries that we discussed in the class, the OpenCV and json-simple libraries. The first function in the file to be implemented was CsvToJson. This function used the CSVReader to read the string that came from the Main file, the list is put into a string array for it to be iterated through. I had to implement a couple of JSONArray fields so that the data can be iterated through. It checks for the length of the CSV file, iterates through it all, and assigns the needed sections of data to their new respective JSON data fields, and this is then put into the correct JSON format that was also set up.
  The next thing implemented into the Conversion file was the JsonToCsv function. This function essentially does the same thing as the CsvToJson, except just the other way around. It sets up the StringWriter and CSVWriter objects so that the correct format is already implemented. The JSON parser, JSONObject, and JSONArray items are also initialized so that the columns, rows, and data are all set up the correct way, as done the same with the CsvToJson function from above. It then checks for the column size and reads through it all so that it can then be placed into the correct holder and be read into the newly created CSV file. Once the data is all converted from both methods, we can then go back to the end of the Main file so that the System.out.println can print out the correctly converted data to the console.
  As surprised as I was, the project was able to convert and print out the needed data the correct way as described in the instructions. Before getting it correct, what surprised me the most was how specific I needed to be with some of the formattings so that the data was printed out the correct way. This was not what I thought my biggest issue would be when starting this assignment, but to my surprise, it was what gave me the most trouble from what I remember. 
  When working on and completing this assignment, I was able to learn a lot more about how GitHub worked, and the ins and outs of pushing and committing your work to the repository that I had to set up for the assignment. I also got a better understanding of how it can be easier to use the libraries that are given to us, as opposed to manually trying to compute everything that is needed to be done, as it can be much harder and a lot more tedious. We did not fully create everything in these files, and some of the setups was already done for us by Mr. Snellen before he assigned us this project, so I would not have anything that I would change about it, as it was meant to be designed this way. 
  
