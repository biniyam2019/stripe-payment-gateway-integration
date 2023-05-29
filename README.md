#stripe-payment-gateway-integration
1. Clone the repository:

   ```shell
   git clone https://github.com/biniyam2019/stripe-payment-gateway-integration

    Navigate to the server folder:

    shell

cd server

Create a .env file in the server folder.

Open the .env file and add the following configuration values:

plaintext

    # .env

    DOMAIN="http://localhost:4242"
    PAYMENT_METHOD_TYPES="card,ideal,googlepay"
    PRICE="ADD_YOUR_STRIPE_PRICE_ID"
    STATIC_DIR="../client"
    STRIPE_PUBLISHABLE_KEY="ADD_YOUR_STRIPE_PUBLISHABLE_KEY"
    STRIPE_SECRET_KEY="ADD_YOUR_STRIPE_SECRET_KEY"
    STRIPE_WEBHOOK_SECRET="ADD_YOUR_STRIPE_WEBHOOK_SECRET"

    Replace the ADD_YOUR_STRIPE_PRICE_ID, ADD_YOUR_STRIPE_PUBLISHABLE_KEY, ADD_YOUR_STRIPE_SECRET_KEY, and ADD_YOUR_STRIPE_WEBHOOK_SECRET values with your own Stripe API keys and Price ID. Please make sure to keep these keys and ID confidential and not share them publicly.

    Note: Do not include any quotation marks around the keys or ID.

    Save the .env file.

Running the Server

    Install the necessary dependencies:

    shell

npm install

Start the server:

shell

    npm start

    The server will now be running and ready to accept requests.

Additional Notes

    Make sure to properly configure any other required environment variables in the .env file for the server to function correctly.

    Ensure that the STATIC_DIR value points to the correct directory path of your client-side code.

    For any further questions or issues, please reach out to biniyamwolde2019@gmail.com
