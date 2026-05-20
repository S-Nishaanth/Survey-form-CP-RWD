# Hotel Feedback Survey Form

A semantic, responsive HTML survey form built as part of the Responsive Web Design certification. This project collects detailed guest experience data for a hotel establishment, ensuring high web accessibility and robust browser-side validation.

## 🚀 Project Status: Iteration 1 (HTML Skeleton)

The foundational HTML structural architecture is complete. This initial milestone focuses entirely on structural semantics, form input mechanics, clean backend data pairing, and semantic layout boundaries before introducing custom CSS styling.

## 🛠️ Features Implemented

### 1. Personal Information Section
* **Data Fields:** Name (`type="text"`), Email (`type="email"`), and Age (`type="number"`).
* **Validation:** Mandatory constraint layers applied to the name and email fields using the `required` attribute. Age range bound strictly between `min="5"` and `max="80"`.
* **UX Enhancements:** Inline user guidance provided via explicit descriptive placeholder text across fields.

### 2. Experience Details Section
* **Waiter Assessment Dropdown:** Implemented a single-choice `<select>` menu containing five designated staff options.
* **Cuisine Selection Matrix:** Integrated a multi-choice checkbox array (`type="checkbox"`). All options share the `name="cuisine"` attribute for structured data packaging upon submission.
* **Food Quality Feedback:** Constructed a mutually exclusive radio button array (`type="radio"`). Linked by a shared `name="quality"` attribute to ensure browser-enforced single-choice selection logic.

### 3. Open Feedback & Submission
* **Textarea Block:** A `5x50` character-bounded multi-line input box dedicated to unfiltered user suggestions.
* **Submission Trigger:** Explicitly bound a `type="submit"` action button to process the wrapped `#survey-form` state.

## 🧩 Architectural Highlights & Best Practices

* **Backend-Ready Mechanics:** Every interactive input field is armed with a clean `name` attribute and corresponding explicit `value` properties to package seamless Key-Value data strings upon form dispatch.
* **Accessibility (A11y Alignment):** Label-to-input pairing is structurally secured via matching `<label for="ID">` and `<input id="ID">` pairings. Tapping textual content automatically moves active browser focus straight into the respective form field.
* **Semantic Zoning:** Divided into isolated logical modules using clean `<fieldset>` containers paired with descriptive `<legend>` block text headers.

## 📋 Next Phase: CSS Implementation Plan

* Introduce a global layout engine using CSS Flexbox/Grid for form centering and consistent spatial distribution.
* Apply clean UI variables for field focus states, custom typography, and soft borders.
* Normalize line spacing by extracting native `<br>` tags out of the HTML document structure and replacing them with native CSS padding/margins.
