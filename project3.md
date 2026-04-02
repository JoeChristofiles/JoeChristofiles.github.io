[Back to Portfolio](./)

AD-Library
===============

-   **Class:CSCI-383** 
-   **Grade:P** 
-   **Language(s):JavaScript, Vue, CSS, HTML** 
-   **Source Code Repository:** [AD-Library](https://github.com/JoeChristofiles/CSCI-383)  
    (Please [email me](mailto:jachristofiles@student.csuniv.edu?subject=GitHub%20Access) to request access.)

## Project description

This project is a frontend prototype of a searchable advertisement library built from a client-style specification. The goal was to replace folder-based storage with a system that allows users to search, filter, and explore ad content in a structured way without relying on inconsistent file naming or manual organization.

The application is built with Vue 3 and uses a modular component-based architecture. Core logic is separated into composables responsible for ad ingestion, transformation, normalization, and filtering. The system supports two main input sources: CSV metadata and local media uploads. CSV data is mapped into normalized ad objects, while uploaded media is converted into displayable records and merged into the active dataset.

A major focus of this project was handling inconsistent real-world data. The system normalizes labels such as language, gender, platform, and action so filtering remains consistent regardless of input format. It also derives additional attributes from ad content, including religion, holidays, keywords, and emotions, allowing for more useful filtering than what exists in the original data.

Filtering is handled through a dedicated composable that computes filter values dynamically and applies multi-dimensional filtering in real time. Users can search across multiple fields and refine results using structured filters such as language, platform, region, content type, and derived metadata.

This implementation follows the original project requirements focused on search, filtering, and usability for non-technical users, while extending the system with additional normalization and derived data to improve consistency and scalability.

My work focused on frontend architecture, CSV-to-object transformation, metadata normalization, and filtering logic. The goal was to build a maintainable system that can scale with additional data and support future integration with a SharePoint-based workflow.

## How to run the program

This is a Vue 3 application built with Vite and is run from the project root directory.

```bash
npm install
npm run dev
```

## UI Design

This application uses a web-based interface that allows the user to search, filter, and inspect advertisement records without relying on folder navigation or raw metadata. The user can upload CSV files, upload local media, search across multiple fields, apply filters, and open individual ads for detailed viewing. All interaction occurs through the interface, with results updating dynamically based on user input.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 1. Main library view showing ad cards, search, and filter controls.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 2. Filter interface used to narrow ads by structured metadata fields.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 3. Detailed ad view showing expanded metadata and media content.

## 3. Additional Considerations

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [AD-Library](https://github.com/JoeChristofiles/CSCI-383).

[Back to Portfolio](./)