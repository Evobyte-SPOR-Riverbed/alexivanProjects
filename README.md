A Web Application developed using Dotnet & Angular

Technologies used: Dotnet & Angular, Entity Framework, Microsoft SQL  Angular Material, Angular Forms, Bootstrap, nG Bootstrap, rxJs, chartJs, Auth0 jwt, and probably others I can't remember.

The app is a Portfolio Tracker that uses authentication to help a user keep track of all their assets(stocks, crypto, etc) in a single portfolio, for better management and analysis. The application only stores the assets information and not the literal assets. For now, it's only set up for crypto since the Binance API since is the only one I could find that offers free unlimited requests.

The application currently has the current functionalities: 
Login and Logout component using jwt tokens and auth0,
Portfolio component which tracks all personal assets and shows real time price updates(from Binance API), has CRUD functionality,
TradeTracker component which displays all the user trades. This is where a lot of data processing and calculations happens to help the user keep track of their most profitable trades and assets over time. Has CRUD functionality,
Analytics component which displays relevant assets and trades data over time, also price evolutions over time. Everything shown as Graphs,
News component which displays latest Economic News directly from an external API.
More to come.


The application does a lot of information processing directly from the API calls, mainly using rxJS, and also some data processing from the database, using Controllers and Entity Framework. The Graphics are nicely displayed using ChartJs. Authentication and Authorization is handed using jwt tokens and auth0. The themes, colors and positioning is handled using a comibation of Bootstrap and Angular Material. Login and Logout forms are handled using Boostrap + Angular Forms. Pagination is handled using ngBoostrap. Since there is little data comming from the database on this project, most data is comming from external API's and processed directly on the Front-End.


