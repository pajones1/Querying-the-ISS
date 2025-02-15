# Querying-the-ISS

# Querying the International Space Station (ISS) 🚀

## Overview
This project queries the **International Space Station (ISS) location and pass times** using the [OpenNotify API](http://open-notify.org/), a simple, authentication-free API that provides real-time data about the ISS.

The project demonstrates:
- Fetching the **current location** of the ISS.
- Determining the **next visible pass times** over a given location.
- Extracting and displaying **JSON responses** from the API.
- Formatting **human-readable outputs** for better interpretation.

## Data Source
This project utilizes the **OpenNotify API**, which provides:
- `http://api.open-notify.org/iss-now.json` → Fetches the **current latitude & longitude** of the ISS.
- `http://api.open-notify.org/iss-pass.json?lat=<LAT>&lon=<LON>` → Fetches the **next pass times** over a specific location.

## Technologies Used
- **Python 3**
- **Requests**: For sending API requests.
- **JSON**: For handling API responses.
- **Datetime**: For formatting timestamps.

## How It Works
1. The script **fetches real-time ISS location data**.
2. It prints the **status code and API response**.
3. The script can also determine the **next pass times** over a specific latitude and longitude (e.g., Sydney: `-33.87, 151.21`).
4. Outputs are formatted for **easy readability**.

## Installation & Usage
### Prerequisites
Ensure you have **Python 3** installed along with the required libraries:
```bash
pip install requests
