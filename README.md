# Hotel Feedback Survey Form

A semantic, responsive HTML survey form built for the freeCodeCamp Responsive Web Design certification. This project establishes the structural code architecture required to collect detailed guest experience data for a hotel establishment, maximizing web accessibility and client-side data validation.

## 🚀 Project Status: Completed (Semantic HTML Focus)

This repository serves as a finished, production-ready blueprint for structural HTML forms. The goal of this standalone iteration was to implement precise semantic data boundaries, interactive element pairings, and server-ready field attributes before graduating to multi-file layout frameworks.

## 🛠️ Features Implemented

### 1. Personal Information Section
* **Data Fields:** Name (`type="text"`), Email (`type="email"`), and Age (`type="number"`).
* **Validation:** Explicit mandatory constraint layers applied to name and email fields using the `required` attribute. Age bounds locked strictly between `min="5"` and `max="80"`.
* **UX Enhancements:** Inline user guidance provided via detailed, descriptive placeholder text across fields.

### 2. Experience Details Section
* **Waiter Assessment Dropdown:** Implemented a single-choice `<select>` menu containing five designated staff choices.
* **Cuisine Selection Matrix:** Integrated a multi-choice checkbox array (`type="checkbox"`). All options share the `name="cuisine"` attribute for structured data packaging upon submission.
* **Food Quality Feedback:** Constructed a mutually exclusive radio button array (`type="radio"`). Linked by a shared `name="quality"` attribute to enforce automated single-choice browser logic.

### 3. Open Feedback & Submission
* **Textarea Block:** A `5x50` character-bounded multi-line input box dedicated to unfiltered user suggestions.
* **Submission Trigger:** Explicitly bound a `type="submit"` action button to process and dispatch the wrapped `#survey-form` state.

## 🧩 Architectural Highlights & Best Practices

* **Backend-Ready Mechanics:** Every interactive input field is armed with a clean `name` attribute and corresponding explicit `value` properties to package seamless Key-Value data strings upon form dispatch.
* **Accessibility (A11y Alignment):** Label-to-input pairing is structurally secured via matching `<label for="ID">` and `<input id="ID">` pairings. Tapping textual content automatically moves active browser focus straight into the respective form field.
* **Semantic Zoning:** Divided into isolated logical modules using clean `<fieldset>` containers paired with descriptive `<legend>` block text headers.
