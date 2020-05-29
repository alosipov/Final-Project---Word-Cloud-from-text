# Final-Project---Word-Cloud-from-text
Final Project for Python Crash Course from Google powered by Coursera

Project goal 
Create a dictionary with words and word frequencies that can be passed to the generate_from_frequencies function of the WordCloud class.

Use this code to generate the word cloud image:

cloud = wordcloud.WordCloud()
cloud.generate_from_frequencies(frequencies)
cloud.to_file("myfile.jpg")

Input file
For the input file, you need to provide a file that contains text only. For the text itself, you can copy and paste the contents of
a website you like. Or you can use a site like Project Gutenberg (https://www.gutenberg.org/) to find books that are available online.
You could see what word clouds you can get from famous books, like a Shakespeare play or a novel by Jane Austen.
