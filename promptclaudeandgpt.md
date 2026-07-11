PROMPTS FOR FAQ SECTION ONLY:



Chatgpt prompt:
Create a modern FAQ section for a technology conference website called "DevConf 2026".

The section should include:
- A main heading: "Frequently Asked Questions"
- A short descriptive paragraph explaining that users can find important information before joining the conference.
- Use semantic HTML5 elements.
- Use <details> and <summary> elements to create expandable FAQ items.
- Include multiple FAQ questions related to a developer conference, such as:
  - Who can attend the event?
  - Are sessions recorded?
  - Can tickets be transferred?
  - Is food provided?
  - How can attendees contact organizers?
- Each question should have a short, realistic answer.
- Keep the structure clean, accessible, and easy to style with CSS later.
- Wrap the entire section inside a single <section> element with an appropriate class name.


Claude Prompt

        <section class="faq">
            <h2>Frequently Asked Questions</h2>
            <p>Everything you need to know before joining DevConf 2026.</p>

            <details open>
                <summary>Who can attend DevConf 2026?</summary>
                <p>Anyone passionate about technology, from students to industry professionals, is welcome.</p>
            </details>

            <details>
                <summary>Will the sessions be recorded?</summary>
                <p>Yes. All attendees receive access to recorded sessions based on their ticket type.</p>
            </details>

            <details>
                <summary>Can I transfer my ticket?</summary>
                <p>Yes. Tickets can be transferred to another attendee before September 15, 2026.</p>
            </details>

            <details>
                <summary>Will food be provided?</summary>
                <p>Lunch, coffee breaks, and refreshments are included with every conference pass.</p>
            </details>

            <details>
                <summary>How do I contact the organizers?</summary>
                <p>Email us at <strong>support@devconf2026.com</strong> and we'll respond within 24 hours.</p>
            </details>
        </section>                    make a very good modern day faq section only css design for this html code. the design should be so cool that everyone likes it. modern day website and so much interective and beautiful colours and cool design            just give me the code man . for this section only. it should not effect the whole css file. just for this section. only give the css code . dont build
```