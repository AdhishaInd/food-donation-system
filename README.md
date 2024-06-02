# THE HELP: Waste Food Management and Donation System

## Project Group 12

- Dehipitiya D.W.G.A.J.B. (20/ENG/026)
- Indumina M.A. (20/ENG/185)
- Herath H.M.D.N. (20/ENG/055)

## Table of Contents

1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Architecture of the System](#architecture-of-the-system)
4. [Technologies Used in Developing](#technologies-used-in-developing)
5. [GUI with Guidance](#gui-with-guidance)
6. [Challenges](#challenges)
7. [Future Improvements](#future-improvements)
8. [Project Setup](#project-setup)

## Introduction

In a world brimming with technological advancements and agricultural abundance, food waste remains an unconscionable reality. An estimated one-third of all food produced for human consumption ends up discarded, amounting to a staggering 1.3 billion tons annually. This colossal figure represents not only a squandering of precious resources but also a significant contributor to greenhouse gas emissions, further exacerbating the climate crisis we face.

Amidst this paradox of surplus and scarcity, nearly 690 million individuals worldwide grapple with the harsh realities of hunger. This stark contrast highlights the urgent need to bridge the gap between food surplus and food insecurity. Our project emerges as a beacon of hope, seeking to address this critical challenge by harnessing the power of technology and collaboration.

Through a user-friendly food donation system, we aim to seamlessly connect food donors with charity organizations, ensuring that surplus food reaches those who need it most. Our system will serve as a centralized platform, streamlining the donation process, fostering collaboration, and bridging the divide between abundance and deprivation.

## Objectives

- Reducing food waste by connecting restaurants with excess food to NGOs which can distribute the surplus food to the needy.
- Creating efficient connections between restaurants/hotels and NGOs.
- Encouraging more restaurants and hotels to participate in food donations.
- Promoting a culture of charitable giving among businesses, leading to increased food donations and greater social impact.
- Reducing food insecurity and food shortage for vulnerable people like the poor and homeless.
- Promoting efficient food redistribution.
- Enabling communication and easy interaction among NGOs, donors, and deliverers.
- Reducing food waste and diverting it to composting facilities, mitigating greenhouse gas emissions and conserving precious resources.

## Architecture of the System

### Mobile/Web App

Our food donation app is designed to cater to the needs of three distinct user types: organizations, employees, and donors. The app is accessible through both Android and Windows platforms, allowing users to access it from anywhere at any time. The app has been developed with a user-centric approach, providing each user type with a unique interface tailored to their specific needs.

### Server

To support the functionality of our food donation app, we utilize APIs to connect the client-side app with the server-side infrastructure. The server-side architecture handles the processing of requests from the client-side app, ensuring that all user actions are quickly and efficiently processed. Our APIs are designed to be easily accessible and customizable, allowing us to quickly adapt to changing user needs and requirements.

### Database

Our food donation app is built on a MySQL database, providing a reliable and efficient platform for storing and managing the app's data. The database is designed to handle a high volume of transactions, ensuring quick and efficient processing of user requests. Multiple levels of data security are implemented to protect user data from unauthorized access or modification.

### Admin

System administrators manage the app's overall functionality and ensure that all user actions align with our mission and values. The system administrator interface allows administrators to approve or reject applications to register organizations or donors, manage user accounts, view donation statistics, and generate reports related to app usage and performance.

## Technologies Used in Developing

- **Flutter** - 3.10.6
- **Uvicorn** - 0.23.1
- **FastAPI** - 0.100.0
- **MySQL** - 8.0.36

## GUI with Guidance

### Organization App

- **Figure 02:** Shows a list of food requests sent to find donors. Add a new request by tapping the floating action button ‘Request’.
- **Figure 03:** Select a category, enter the required amount, and specify if the food should be collected in the organization or directly delivered.
- **Figure 04:** By clicking on a tile in the request list, a bottom sheet can be opened to show all information about the request and provide options to chat with donors or members and cancel the request.
- **Figure 05:** See members of your organization. To add an employee, tap the + sign.
- **Figure 06:** Enter the member ID to add a member.
- **Figure 07:** The bottom sheet shows full information about the member and a button to remove them from the organization
