# azure-weather-integration
Built an Azure Logic App integration that retrieves weather data from a public REST API on a scheduled basis. The workflow parses and validates the JSON response, stores valid data in Azure Blob Storage, and handles invalid responses with structured error handling using conditional logic and termination actions.

This project demonstrates an Azure Logic App integration that retrieves weather data from an external API and stores it in Azure Blob Storage.

Architecture

Recurrence Trigger
→ HTTP Request to Weather API
→ Parse JSON
→ Data validation
→ Store data in Azure Blob Storage
→ Error handling using Terminate action

Technologies

- Azure Logic Apps
- Azure Blob Storage
- REST API integration
- JSON parsing
- Conditional logic
- Error handling


<img width="1438" height="837" alt="image" src="https://github.com/user-attachments/assets/10ad41a4-f556-4db2-859f-ccedc9b1a105" />
