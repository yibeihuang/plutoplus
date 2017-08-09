To run the script, you can init a local server in the same directory as this one (it will auto
search for the index.html file):
python -m SimpleHTTPServer

The main jsx file is App.jsx, it calls other .jsx files such as Map.jsx, sidebar.jsx
All the files are imported from index.html, remember to import the most import file last so that it can find the files it is calling.
We can add more functions by adding .jsx files.
