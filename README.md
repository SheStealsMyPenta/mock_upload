already Deploy in Vercel https://mock-upload.vercel.app/
 1.	What did you choose to mock the API and why?
	•	I chose axios-mock-adapter because it can straightforwardly simulate axios requests, making it easy to set delays, errors, and status simulations. This allows us to quickly validate front-end logic without setting up a real backend.
	2.	If you used an AI tool, what parts did it help with?
	•	I used ChatGPT to help set up the initial structure, particularly the core implementation of task polling and state management.
	3.	What tradeoffs or shortcuts did you take?
	•	For rapid implementation, I did not use a complex library (like Redux) for state management; instead, I used useState and useRef.
	•	As for UI design, I only implemented the most essential features without overly refining aesthetics.
	4.	What would you improve or add with more time?
	•	I would use React Query for more efficient polling.
	•	I’d also add or improve unit/integration tests.
	•	I would enhance error messages and refine the file upload UI for a better user experience.
	5.	What was the trickiest part and how did you debug it?
	•	The trickiest part was handling the task polling retry mechanism. Initially, the logic for counting retries wasn’t correct. I debugged it by printing status updates to the console and adjusting the logic step by step until it worked.
