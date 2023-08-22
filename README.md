# Pizza Menu

## Developing an online menu for a pizza restaurant

TBC

## Planning the application

1. Gather app requirements and features
2. Divide the app into 'pages'
   1. Think above overall and page-level UI
   2. Break the UI into components
   3. Design / build static version
3. Divide the app into feature categories
   1. State management and data flow
4. Implement tech stack - libraries

## App Requirements

TBC

## Features & Pages

1. User -> Homepage /
2. Menu -> Pizza menu /menu
3. Cart -> Cart /cart
4. Order -> Place a new order /order/new & Look up an order /order/:orderID

## State Management / Tech Stack

Each will have own state slice

1. User: Global UI state
2. Menu: Global remote state (menu is fetched from API)
3. Cart: Global UI state
4. Order: Global remote state

Routing: ReactRouter
Styling: Tailwindcss
Remote State-Management: ReactRouter (data fetching in v6.4+ / render-as-you-fetch approach)
UI State-Management: Redux
