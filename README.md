# Dinesh-Kumar_FrontEnd

Front End Assignment.

Question 1: Explain what the simple List component does.

The List component in React is used to render a collection of similar items in the form of a list. It allows you to display data in an organized and structured manner, making it easy for users to scan through and find the information they need.
In React, you can create a List component by mapping an array of data to a set of list items using the map function. This allows you to dynamically generate the list items based on the data you have, without having to hardcode each item individually.


Question 2: What problems / warnings are there with code?
Answer: Different problems / warnings we get are:

First error was we need to install the dependencies named 'props-types' by running 'npm i props-types'
Second error was in useState of 'setSelectedIndex' and 'selectedIndex' are given in reverse order. We need to reverse it like below given: const [selectedIndex, setSelectedIndex] = useState(null);
Third error was in this piece of code: WrappedListComponent.propTypes = { items: PropTypes.array(PropTypes.shapeOf({ text: PropTypes.string.isRequired, })), PropsTypes.arrayOf instead of PropsTypes.array and the third error was using PropsTypes.shape instead of PropsTypes.shape.
