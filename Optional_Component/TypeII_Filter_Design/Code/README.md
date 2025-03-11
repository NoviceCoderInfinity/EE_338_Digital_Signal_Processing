## Instructions to run the HTML code

You don't need to download any external libraries/environment to run the code. Any modern-day browser will suffice. To run the `.html` files, ensure that you're connected to the internet, since it loads the required libraries from the internet.

### Running Offline

If you want to run the code offline, follow these steps:

1. **Download the required libraries**

   - Download the following libraries:
     - [math.js](https://cdnjs.cloudflare.com/ajax/libs/mathjs/11.3.2/math.js)
     - [Plotly.js](https://cdn.plot.ly/plotly-2.20.0.min.js)

2. **Update the script references in your HTML file**
   Replace the script links in the `<head>` section of your HTML file with local references, like this:

   ```html
   <script src="math.js"></script>
   <script src="plotly-2.20.0.min.js"></script>
   ```

3. **Open the HTML file in a browser**

By following these steps, you can run the HTML file without an internet connection.
