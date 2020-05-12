# Thinking-React

JS library built by Facebook
	• Designed to build very interactive and dynamic UI.

Key Ideas to think in React
	• Declarative (We make how the application to look like)
	• JSX (instead of using JS, it is going to use its slight extension. i.e, JS X, here we can treat html code as a value
	  Ex: const foo =<h1>HELLO</H1>)
	Libraries(React, ReactDOM, Babel( Translate the JSX code into JS code, which the browser can understand)
	
	<script src = "https://unpkg.com/react@16/umd/react.development.js" crossorigin></script>
	
	<script src = "https://unpkg.com/react-dom@16/umd/react-dom.development.js" crossorigin></script>
	
	<script src = "https://unpkg.com/babel-standalone@6/babel.min.js"></script>
	
	• Components
		○ class Hello extends React.component {
			render() {
				return <h1>Hello!</h1>
			}
		}
	• State
		○ change the data, change the state/view of application
	
Imperative means(We write code to what to do exactly)


props :
attributes that we are going to provide into the component and the component never changes its own props, The information of how the component should behave is never going to change
State:
the component has, and might change some point in the future 
Ex : Name
