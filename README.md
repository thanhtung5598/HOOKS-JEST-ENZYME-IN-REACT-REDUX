Module should be install
    "enzyme": "^3.11.0",
    "enzyme-adapter-react-16": "^1.15.2",
    "enzyme-to-json": "^3.4.4",
    "jest": "^24.9.0",
    "react-test-renderer": "^16.12.0"
    
				----------------------------------------------------------------
React Redux now offers a set of hook APIs alternative connect() Higher Order Component
As with connect(), you should start by wrapping your entire application in a <Provider> component
The selector is approximately equivalent to the mapStateToProps argument to connect
However, there are some differences between the selectors passed to useSelector() and a mapState function:
	The selector may return any value as a result, not just an object.
	The selector function does not receive an ownProps argument.However, props can be used through closure

When the function component renders, the provided selector function will be called and its result will be returned from the useSelector() hook.

You may call useSelector() multiple times within a single function component.

With useSelector() returning a new object every time

*Equality Comparisons and Updates*
_ connect() just compared the individual fields. With useSelector(), returning a new object every time

What is the difference of using hooks or connect to my React-Redux project ?
There are two major differences:
	*Scope
	Connect can be used with both React class components and function components whereas hooks can be used with function components only.
Việc dùng useSelector sẽ giúp bạn quản lý redux state chặt chẽ hơn.

				----------------------------------------------------------------
Jest là một testing framework với mục đích là để kiểm thử javascript cũng như React.
Quy định viết test thì các file dùng để kiểm thử đều đặt trong thư mục __test__
tên file test tương ứng với file gốc với phần mở rộng là .test.js hoặc .spec.js.

******** Snapshot testing dùng module react-test-rendere
******** Matchers:toBe là một trong những matchers cua Jest.
******** Enzyme: là một tiện ích dùng trong kiểm thử Javascript cho React.
         Shallow Rendering & Full DOM Rendering

