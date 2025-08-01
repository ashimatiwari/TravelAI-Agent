# AI-Powered Travel Planner Agent
A capstone project built using IBM Watsonx and Granite Foundation Models to generate efficient, real-time, and personalized travel plans based on natural language input.

## Problem Statement
Trip planning involves selecting destinations, booking transport and accommodations, checking weather, and building itineraries. This is often time-consuming and confusing for users.

## Solution Overview
The agent automates the process by:
- Accepting natural language inputs (destination, budget, dates, preferences)
- Collecting live data on weather, transport, and attractions
- Generating a personalized, day-wise travel itinerary
- Allowing updates and regeneration as needed

## How It Works
1. **User Input**: Natural language query
2. **Data Collection**: Real-time data from APIs
3. **AI Processing**: NLP using Watsonx + Granite
4. **Result Output**: Structured travel plan with routes and weather info

## 🔍 Example Workflow
**User Query:**  
*"Plan a 4-day trip to Manali in October with a budget of ₹15,000. I prefer nature spots and moderate climate."*

**Agent Understanding:**  
→ Destination: Manali  
→ Duration: 4 days  
→ Budget: ₹15,000  
→ Preferences: Nature, moderate climate

**Agent Actions:**  
- Fetches weather, transport, and hotel info  
- Gathers nearby nature spots and attractions  
- Builds a personalized itinerary within budget

**Sample Output Itinerary:**

| Day | Location/Activity | Notes |
|-----|-------------------|-------|
| 1 | Arrival in Manali, check-in, Mall Road walk | Local market visit |
| 2 | Solang Valley & Anjani Mahadev Trek | Weather: Sunny 18°C |
| 3 | Hidimba & Manu Temples | Free time for cafes |
| 4 | Local sightseeing + Departure | Check-out |

> ✏️ Editable Output:  
> "Add rafting on Day 2" → Agent regenerates plan accordingly.

## Technologies Used
- IBM Cloud Lite
- Watsonx.ai
- Granite Foundation Model
- OpenWeatherMap API
- Google Maps Platform
- Built-in Agent Tools: Search, Summarize, Weather, Calculator

## Features
- Natural language input
- Real-time itinerary generation
- Weather-aware suggestions
- Location-based data integration
- Editable and regenerable output

## Sample Output
<p align="center">
  <img src="./assets/itinerary-output-1.png" width="600" alt="Generated Itinerary Screenshot 1">
</p>
<p align="center">
  <img src="./assets/itinerary-output-2.png" width="600" alt="Generated Itinerary Screenshot 2">
</p>

## Conclusion
This AI-powered planner streamlines the travel planning process using real-time data and NLP. It intelligently creates custom itineraries, recommends places and accommodations, and dynamically updates based on changes, enhancing the overall user experience.
