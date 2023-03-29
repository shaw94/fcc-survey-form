Lessons Learned

- If a label is too long, it probably is not a label, it must be a <p> element

- A div that contains both input and label is refered to as a form-group. Which is also the name used as the classname of that div.

- Buttons are also in a form group, which I find weird

- Text inputs are given the classname of 'form-control' other types are given classnames of 'input-inputtype' for example, input-radio, input-checkbox input-textarea

  - A selectbox is also considered a form-control

- The first option in a select element, is preferable to have the following attributes: <option select disabled value>Please select an option</option>

That way it has no value, it is selected, and also disabled

- If labels need to be distinguished, they are given ids, the naming convention for it is like so:
  <label for="email" id="email-label">Email</label>

- To know which element to use, you should look at the content within it.