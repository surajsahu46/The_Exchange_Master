
# The Exchange Corner

The Exchange Corner is a web application that provides currency conversion and obtaining historical exchange rates. Users can make currency conversions, explore historical exchange rates, and add their favorite currency pairs. Additionally, the app enhances the user experience with informative sections, such as one that shows the most common conversions for the selected base currency. All this within an accessible, simple and harmonious interface.

---

## Features

- Performs currency conversions quickly and accurately.
- Retrieves real-time exchange rates for a wide variety of currencies.
- Accesses historical exchange rates for analysis and tracking.
- Adds conversions to a favorites system for quick and convenient access.
- Explores the most common currencies associated with the currency you are searching for.
- Enjoys a simple and harmonious interface for a pleasant user experience.
- Granular and user-friendly error handling through the ErrorBoundary component.
- Implementation of internationalization with next-intl, offering users the option to view content in  English or Spanish.
- Utilizes a toast system to notify the user of the outcomes of various actions and enhance their experience in the application.
- Implementation of a streaming system when fetching data, leveraging the features of Next.js.
- Access and updates data granularly, improving the efficiency and speed of the application.
- Provides a smooth user experience when dynamically loading information.
- Enhanced user experience during data loading thanks to the implementation of skeleton components.

## Technologies Used

- <a href="https://react.dev/" target="_blank">**React**</a>: A JavaScript library for building interactive user interfaces.
- <a href="https://next-intl-docs.vercel.app/docs/getting-started" target="_blank">**Next.js**</a>: A React framework that enables server-side rendering, automatic code splitting, and simplified routing for building powerful and efficient web applications.
- <a href="https://www.typescriptlang.org/docs/" target="_blank">**TypeScript**</a>: A superset of JavaScript that adds static types and other features to the language syntax.
- <a href="https://www.npmjs.com/package/dotenv" target="_blank">**Dotenv**</a>: A zero-dependency module for loading environment variables.
- <a href="https://axios-http.com/" target="_blank">**Axios**</a>: A popular library for making HTTP requests.
- <a href="https://tailwindcss.com/" target="_blank">**Tailwind CSS**</a>: A utility-first CSS framework that simplifies styling by providing low-level utility classes, enabling a straightforward and fast approach to building modern and responsive interfaces.
- <a href="https://next-intl-docs.vercel.app/" target="_blank">next-intl</a>: A Next.js library for internationalization (i18n) that facilitates easy management of translations and localization in your application. 
- <a href="https://www.alphavantage.co/" target="_blank">AlphaVantage</a>: AlphaVantage API is a financial data provider that offers a wide range of data, such as currency conversion and historical rates.

## Project Structure

- `public`: Contains static assets such as images and icons used in the application.
- `public/locales`: Contains json files used in internationalization.
- `src/app`: Contains the main files and pages of the application.
- `src/components`: Contains reusable components used in different parts of the application.
- `src/context`: Contains context providers and consumers used for state management.
- `src/models`: Contains TypeScript interfaces, models or types used for defining data structures.
- `src/services`: Contains Axios instances, interceptors, and calls to the AlphaVantage API to perform currency conversions and obtain historical data.
- `src/utilities`: Contains utilities and helper functions used in the application.

## Authors

- Suraj Sahu

If you have any questions, concerns or interest, feel free to contact me.
