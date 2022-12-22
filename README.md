# Crypto-Currency-Tracker
This is a simple Crypto Currency Tracker I used to practice clean code, and to implement into my business "Donate Crypto".


TRY THIS FOR FURTHER USE.

1. In the same directory as app.py, create a directory named templates and within that directory create a file named index.html with the following contents:(Minus the spaces between the first letter of each command)

**

<!d octype html>
<h tml>
  <h ead>
    <t itle>Cryptocurrency Tracker</title>
  </h ead>
  <b ody>
    <h 1>Cryptocurrency Tracker</h1>
    <f orm action="/price" method="get">
      <l abel for="currency">Enter a cryptocurrency:</label>
      <i nput type="text" name="currency" id="currency">
      <b utton type="submit">Get Price</button>
    </f orm>
  </b ody>
</h tml>
-->
**

2. This template defines a form that allows the user to enter a cryptocurrency and submit the form to retrieve its price and change.

To run the app, navigate to the directory containing app.py in a terminal or command prompt and run the following command:

**
python app.py
**

3. This will start the development server at http://127.0.0.1:5000/. You can visit this URL in your web browser to view and interact with the cryptocurrency tracker app.

To retrieve the price and change for a specific cryptocurrency, enter the cryptocurrency's ticker symbol in the form and click the "Get Price" button. The app will display the price and change for the specified cryptocurrency.
