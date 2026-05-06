# 💾 mcp-database-query-app - Manage your databases through a simple interface

[![](https://img.shields.io/badge/Download-Application-blue.svg)](https://github.com/Dry-statelyhome866/mcp-database-query-app)

This application connects your databases to the Claude Desktop interface. It allows you to run queries and manage data without writing complex code. You see your tables, run SQL commands, and visualize results directly inside your chat workspace.

## ⚙️ System Requirements

This software runs on any modern Windows computer. Ensure you have the following pieces of software installed:

*   Windows 10 or Windows 11.
*   .NET 8.0 Runtime or newer.
*   Claude Desktop application.
*   Internet connection for database connections.

If you lack the .NET Runtime, the installer will direct you to the Microsoft website to download it. This is a standard step for Windows applications built on this framework.

## 📥 How to Install the App

Follow these steps to set up the software on your machine:

1.  Visit the [official releases page](https://github.com/Dry-statelyhome866/mcp-database-query-app).
2.  Locate the latest version under the "Releases" section.
3.  Download the setup file ending in .msi or .exe.
4.  Open the file and follow the prompts on your screen.
5.  Click Finish once the progress bar completes.

The app icon now appears on your desktop. You can open it to begin the configuration.

## 🚀 Setting Up Your Connection

The application needs permission to talk to your database. You provide these details once, and the app saves them securely.

1.  Open the MCP Database app from your Start menu.
2.  Click the "Add Connection" button on the main dashboard.
3.  Choose your database type from the list.
4.  Enter your database server address.
5.  Provide the port number, your username, and your password.
6.  Click "Test Connection" to confirm the app reaches your data.
7.  Save the profile.

The app supports MSSQL and Postgres databases. It uses secure protocols to ensure your credentials remain private throughout the exchange.

## 💬 Using the App with Claude Desktop

This software integrates into your workflow by acting as a bridge between your database and Claude. Once you set up the application, configure Claude to use it as an extension.

1.  Open the Claude Desktop app.
2.  Access your settings through the profile menu.
3.  Find the section labeled "Extensions" or "MCP Servers."
4.  Click "Add New Server."
5.  Paste the path to the MCP executable provided by this app.
6.  Restart Claude Desktop.

After the restart, you see a small database icon in the chat window. You can now ask questions about your data. For example, you might type "Show me the top five products from my sales table." The app retrieves the data and presents it in a clear format.

## 📊 Visualizing Your Data

The app includes chart support. When you receive a large set of numbers from a query, you can request a visual report.

*   Select the data you want to display.
*   Choose a chart type like bar, line, or pie.
*   Click "Generate Chart."

The app renders the graphic directly within your chat window. This helps you spot trends or issues in your database tables.

## 🛠️ Troubleshooting Common Issues

If the app fails to connect, check these items:

*   Network: Ensure you have access to the server. If your database exists on a company network, you may need a VPN connection.
*   Permissions: Verify that your database user account has read access to the specific tables you want to query.
*   Updates: Check the desktop icon for a small red badge. This indicates a new software update awaits you. Keeping the software current resolves many compatibility errors.
*   Environment Variables: If the app does not launch, ensure you installed the .NET runtime successfully. Restarting your computer often fixes background installation errors.

## 🔐 Privacy and Security

The app processes data locally on your machine. Your database credentials stay inside your local configuration files. This application does not upload your database content to external servers. It only sends the specific data required to fulfill the requests you type into the Claude interface. 

You control which databases connect to the app. You can remove a connection at any point in the dashboard. Deleting the connection clears all stored settings for that specific database.

## 📖 Support and Feedback

This software receives regular updates. You can track progress on the main project page. If you discover a bug or need a feature for a specific database type, open an issue on the GitHub repository. Provide as much detail as possible about the error. Include a description of what you expected to see versus what the app actually displayed. 

Clear communication helps the development team fix problems faster. Avoid sharing private passwords or sensitive connection strings when you report an issue. Always mask sensitive data before you post logs or screenshots.