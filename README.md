#  Horiseon Website Code Refactor
Refactored Horiseon Website that follows accessibility standards for search engine optimization.

## HTML Changes
In order for the site to be optimized for search engines, it needs a codebase that meets accessibility standards, which includes:

- Semantic HTML elements
- A logical structure of elements
- Accessible `alt` attributes for `<img>` elements
- Sequential headings
- A succinct, descriptive title

### Semantic HTML Elements
In the original HTML, there was a great lack of semantic elements; only general elements like `<div>` were used. Screen readers would have a difficult time traversing through the code this way, so the solution would be to use semantic elements such as `<section>`, `<article>`, `<header>`, `<footer>`, and `<nav>` instead as shown below:

```html
 <section class="benefits">
        <article class="benefit-info">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt=" " />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </article>
        <article class="benefit-info">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" alt=" " />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </article>
        <article class="benefit-info">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" alt=" " />
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </article>
    </section>

    <!-- Footer -->
    <footer>
        <h3>Made with ❤️️ by Horiseon</h3>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </footer>

    ```

<img src="./horiseon-screenshot.png" />