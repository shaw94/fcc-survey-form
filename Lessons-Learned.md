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

- Margins are used to make seperation between the content, while padding is used to seperate the content from its border if that makes any sense.

- I didn't know the resize property prior to this task

- When height is engaged, it is always min/max which is exactly what everyone recommends.

- Some inputs don't inherit styles from the body, therefore you must enforce that.

- Input border is called outline which you can disable by giving it the value 0.

- The selection state for the inputs is :focus.

