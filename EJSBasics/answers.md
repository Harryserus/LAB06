1. In one sentence: What does res.render(view, data) do?
    res.render(view, data) renders an EJS template and sends HTML to the browser with the provided data injected.

2. What is the difference between <%= %> and <%- %>?
    <%= %> outputs escaped content to prevent HTML injection, while <%- %> outputs unescaped raw HTML.


3. Where does Express look for EJS templates (folder path)?
    Express looks for EJS templates in the views/ directory specified by app.set("views").
