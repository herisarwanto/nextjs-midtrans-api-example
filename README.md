# Next.js API - Example

This project demonstrates the integration of the Midtrans payment gateway utilizing Next.js as the backend.

## Installation

1. **Node.js & Next.js Installation:**
   - Ensure you have Node.js installed. If not, download and install it from [here](https://nodejs.org/).
   - Install Next.js globally or within your project by running:
     ```
     npm install -g next
     # or
     npm install next
     ```

2. **Configuration Setup:**
   - Edit the `.env` file and insert your Midtrans server and client keys.
     ```
     MIDTRANS_SERVER_KEY=your_server_key_here
     MIDTRANS_CLIENT_KEY=your_client_key_here
     ```

3. **Install Dependencies:**
   - Run the following command to install project dependencies:
     ```
     npm install i
     ```

4. **Running the Project:**
   - Start the development server using the command:
     ```
     npm run dev
     ```
   - Access the application locally at `http://localhost:3000`.

## Additional Notes

- Make sure your Midtrans account credentials are correctly set in the `.env` file.
- For detailed API documentation, refer to the [Midtrans API documentation](https://docs.midtrans.com/).
- This app was created as a web service for this app: [flutter-midtrans-example-app](https://github.com/herisarwanto/flutter-midtrans-example-app/).
