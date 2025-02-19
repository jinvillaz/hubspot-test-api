# Notes

- Code Quality and Readability:
  The code can be improved by following good programming practices, such as using object-oriented programming, simplifying functions, modularizing the code, and removing duplicated logic. It would also be beneficial to have better input data validation to prevent unexpected errors. Additionally, implementing TypeScript would provide better typing and make it easier to debug and verify the code. For example, the date filter was modified during testing due to a bug, which made debugging more difficult.

- Project Architecture:
  The architecture could be improved by separating the processing of contacts, companies, and meetings into independent services. Furthermore, centralizing retry logic and error handling would help reduce duplication and increase maintainability.

- Code Performance:
  The performance could be optimized by implementing parallel processing and improving the batch data retrieval from HubSpot. Additionally, optimizing the queue handling could help avoid bottlenecks and improve overall efficiency.

- Bugs/Considerations:
  The date filter was modified due to a bug, which led to changes for testing purposes using a fixed date from 2023.
  There is no specific API indicating which contacts attended a meeting, so we relied on the API that shows contacts associated with a meeting. However, this doesn't confirm whether the contact actually attended the meeting.
