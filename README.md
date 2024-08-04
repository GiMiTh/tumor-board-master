# tumor-board-master

How to run:

1. **Download the XML files of PubMed**: You'll need these files to create the index. Make sure to save them in a location you can easily access.

2. **Set up your IDE**: You'll need to use Eclipse IDE for Enterprise Java and Web Developers. If you haven't installed it yet, you can download it from the official Eclipse website.

3. **Open the LuceneExample Project**: This project contains the LuceneEngine Class that you'll use to create the index.

4. **Set the Paths**: In the LuceneEngine Class, change the first path to where you want to save the index and the second path to where you saved the XML files of PubMed.

5. **Check the Dependencies**: Make sure you have the dependencies of Lucene version 8.9. The dependencies you need are `lucene-queryparser`, `lucene-demo`, `lucene-core`, and `lucene-analyzer-common`.

6. **Create the Index**: Run the LuceneExample project. The indexing process will take about a day or two depending on your PC.

7. **Set up the Server**: To use the Search Engine in localhost, you'll need a server. You can use Tomcat for this. If you haven't installed it yet, you can download it from the official Apache Tomcat website.

8. **Run the luceneweb Project**: This is the project you'll run as a server. Right-click it and select 'Run As' > 'Server', then choose the server you want to run it with (Tomcat if you're using Tomcat).

9. **Check the Dependencies for luceneweb**: The luceneweb project also needs the same dependencies as the LuceneExample project, so make sure you have `lucene-queryparser`, `lucene-demo`, `lucene-core`, and `lucene-analyzer-common` of Lucene 8.9.

And that's it! You should now be able to use the Search Engine in your local host.
