# EstateSpace Front End Development Challenge (Senior React)

Hi! Thank you for your interest in **EstateSpace**.  
Our evaluation process begins with an open-ended coding challenge that we will discuss during your interview. There is not one correct way to approach this challenge. Instead, we want to understand your **technical judgment**, **architecture decisions**, and how you reason about trade-offs.

We appreciate that any coding challenge represents an investment of your time. Please aim to keep the scope reasonable and focus on strong fundamentals rather than completeness. If you are unsuccessful, you are free to reuse the code you developed for this challenge in any way you like.

If you are successful, we will schedule a follow-up interview and use this code as the starting point for a deeper technical discussion.

---

## The Challenge

EstateSpace builds product experiences that consume REST-based services and present data across web and mobile clients. We value clarity in state management, resilience, performance awareness, and maintainable code.

Your task is to build a **Movie Explorer** using the **OMDb API**.

You may implement this as:

- A browser-based application using **React** (Vite or similar), OR
- A **Next.js** application

You can use any styling approach you prefer. Tailwind (or a Tailwind-based solution) is a plus
**TypeScript is a plus and strongly recommended.**

**Time expectation:** ~2–4 hours.

---

## OMDb API

Official documentation:  
https://www.omdbapi.com/

You will need a **free OMDb API key**.

### Common Endpoints

https://www.omdbapi.com/?apikey=API_KEY&s=avatar&page=1

**Movie details by IMDb ID:**

https://www.omdbapi.com/?apikey=API_KEY&i=tt0372784

Notes:

- Pagination is handled via the `page` parameter.
- Some fields may return `"N/A"` (for example, posters). Handle this gracefully.
- The poster URLs returned in the JSON response can be used directly.

---

## Minimum Challenge Requirements

### 1. Search & Results List

- A search input to query movies by title.
- Display a list showing at least:
  - Title
  - Year
  - Poster
- Include explicit states for:
  - Loading
  - Error
  - Empty results

### 2. Pagination

- Implement pagination using OMDb's `page` parameter.
- Provide **Next** and **Previous** controls.
- Pagination must be **URL-driven**:
  - Example: `?q=batman&page=2`
  - Refreshing or sharing the URL should preserve state.

### 3. Movie Details

- Clicking a movie opens a details view (route or modal).
- Fetch movie details
- Display at least:
  - Title
  - Plot
  - Genre
  - Runtime
  - Ratings

### 4. Caching (observable)

Implement a caching strategy such that:

- Navigating back to a previously visited search page does **not** cause a full reload experience.
- Previously visited movie details should not always refetch immediately.
- You may use Tanstack Query, SWR, or a custom approach—document your choice.

---

## Where to Concentrate Your Effort (Senior-Level Focus)

After meeting the minimum requirements, choose **2–3** of the following areas to explore further:

### A. State Management

- Clear separation of:
  - UI state
  - Server state
  - Local vs shared state
  - Performance optimizations
- Explain your decisions and trade-offs.

### B. Search UX Improvements

Examples:

- Debounced search or search-on-enter
- Clear/reset button
- Prevent stale results when typing quickly
- Recent searches persisted locally
- Keyboard-friendly interactions

### C. Resilience & Edge Cases

Examples:

- Graceful handling of missing data
- Avoiding stale or flashing results
- Error boundaries or fallback UI
- Canceling or ignoring in-flight requests

### D. Performance Considerations

Examples:

- Avoid unnecessary re-renders
- Prefetching next pages
- Reasonable memoization
- Efficient list rendering

### E. Testing (light but meaningful)

Add at least one:

- Unit test for a pure function
- Component or integration test for search/pagination or loading/error states

---

## Prerequisites

- Basic understanding of source control (Git).
- All JavaScript should follow modern ES standards.
- TypeScript is encouraged.

---

## Getting Started

1. Fork this repository.
2. Clone the fork to your personal machine.
3. Start coding.
4. Commit changes to your fork as you see fit.

---

## Submission

When you are comfortable with your results, please email your fork to the appropriate EstateSpace contact.  
Please keep your email short and to the point.

Any specific notes, trade-offs, or further information you would like to add should be included in the GitHub project as **CommonMark-compliant documentation**.

Do not feel that you must create a public fork of this repository. You are free to use a private fork or a throwaway GitHub account. If you do so, please let us know so we can provide the GitHub IDs to grant access.

---

## Evaluation Criteria

We will evaluate:

- Correctness and completeness of the minimum requirements
- Code readability and structure
- State management and data-fetching decisions
- Caching strategy and resilience
- Performance awareness
- Pragmatic testing approach
- Clarity of communication in documentation

We realize there are many items to look at when creating a user interface. Please do not feel like like you have to do everything. Please feel free to use any UI/CSS library you wish. Use your strengths to your advantage. If you gravitate more towards design, provide a more visually appealing interface. If you gravitate more towards data consumption, provide more capability by using the API routes. Give us a heads up by documenting your code to let us know where and why you concentrated on certain items.

As you develop your solution, you may have ideas on other avenues to pursue. Please feel free to include them inline as documented source or as additional Common Mark compliant notes in your fork.

We look for creativity, originality, and a good user experience in your application if that's an area you focused on.

We look for readability, good architectural decisions, modularity, and a solid approach to testing in your code.
# License
This project is [MIT licensed][mitlicense].

[g3website]:https://www.griffingroupglobal.com
[git-scm]:https://git-scm.com/
[github]:https://github.com/
[nodejs]:https://nodejs.org/en/
[TDD]:https://en.wikipedia.org/wiki/Test-driven_development
[ES6]:http://www.ecma-international.org/ecma-262/6.0/
[eslint]:https://eslint.org/
[airbnb-eslint]:https://www.npmjs.com/package/eslint-config-airbnb
[mocha]:https://mochajs.org/
[repository]:https://github.com/GriffinGroupGlobal/frontend-challenge
[mitlicense]:https://en.wikipedia.org/wiki/MIT_License
[commonmark]:https://spec.commonmark.org/
[swapi]:https://swapi.co/
