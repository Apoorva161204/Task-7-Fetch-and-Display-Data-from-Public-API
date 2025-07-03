# Task 7: Fetch and Display Data from Public API

## 📋 Task Description
**Objective**: Use JavaScript Fetch API to get user data from a public API and display it on a webpage.

**Tools Used**: VS Code, Chrome Browser, GitHub

**Key Concepts**: Fetch API, Promises, Async JS, JSON, API Integration, Error Handling

## 🚀 Features Implemented

### ✅ Core Requirements (As per PDF)
1. **HTML Container** - Created responsive container for user data display
2. **Fetch API** - Used JavaScript fetch to request data from `https://jsonplaceholder.typicode.com/users`
3. **JSON Parsing** - Properly parsed JSON response from the API
4. **Data Display** - Loops through users and displays name, email, and address
5. **Error Handling** - Comprehensive error handling with try-catch blocks
6. **CSS Styling** - Beautiful, modern styling for displayed data
7. **Network Error Testing** - Handles network errors (test by disabling internet)
8. **Reload Button** - Added reload functionality to refetch data

### 🎯 Additional Features
- **Loading States** - Shows loading indicator while fetching data
- **Success Messages** - Displays confirmation when data loads successfully
- **Responsive Design** - Works on all device sizes (mobile, tablet, desktop)
- **Modern UI** - Glass-morphism design with smooth animations
- **Statistics Display** - Shows total users and last updated time
- **Keyboard Shortcuts** - Press F5 or Ctrl+R to reload data
- **Online/Offline Detection** - Detects and handles connection status changes

## 🛠️ Technical Implementation

### API Endpoint
```javascript
https://jsonplaceholder.typicode.com/users
```

### Key JavaScript Features Used
- **Async/Await** - Modern asynchronous programming
- **Fetch API** - Native browser API for HTTP requests
- **Promise Handling** - Proper error handling with try-catch
- **JSON Parsing** - Converting API response to JavaScript objects
- **DOM Manipulation** - Dynamic content creation and updates
- **Event Listeners** - Handling user interactions and system events

### Error Handling Scenarios
- Network connectivity issues
- HTTP status errors (404, 500, etc.)
- JSON parsing errors
- API timeout issues
- Offline/Online state changes

## 📁 Project Structure
```
├── index.html          # Main HTML file with embedded CSS and JavaScript
├── README.md           # This file - project documentation
└── screenshots/        # Screenshots of the working application (if any)
```

## 🎮 How to Run

1. **Clone the repository**
   ```bash
   git clone [your-github-repo-url]
   cd [repository-name]
   ```

2. **Open the project**
   - Open `index.html` in any modern web browser
   - Or use Live Server extension in VS Code for better development experience

3. **Test the application**
   - Click "Load User Data" to fetch data from the API
   - Use "Reload Data" to refresh the information
   - Test error handling by disabling internet connection

## 🧪 Testing Network Errors

To test error handling as mentioned in the PDF:
1. Load the webpage
2. Disable your internet connection
3. Click "Load User Data" or "Reload Data"
4. Observe the error message displayed
5. Re-enable internet connection
6. Try loading data again

## 📱 Browser Compatibility

- ✅ Chrome (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🎯 Learning Outcomes Achieved

### Interview Questions Covered:
1. **What is Fetch API?** - Implemented modern fetch API for HTTP requests
2. **How do promises work?** - Used both Promise chains and async/await
3. **Synchronous vs Asynchronous?** - Demonstrated non-blocking API calls
4. **Error handling in Fetch?** - Comprehensive error handling implemented
5. **What is JSON?** - Parsed and displayed JSON data from API
6. **What is CORS?** - Handled cross-origin requests
7. **JSON parsing?** - Used response.json() method
8. **Async/await explained?** - Modern async programming demonstrated
9. **HTTP status codes?** - Handled different response statuses
10. **REST API?** - Consumed RESTful API endpoints

### Technical Skills Demonstrated:
- ✅ Asynchronous JavaScript programming
- ✅ API integration and consumption
- ✅ JSON data manipulation
- ✅ Error handling and user feedback
- ✅ Responsive web design
- ✅ Modern CSS techniques
- ✅ DOM manipulation
- ✅ Event handling
- ✅ User experience design

## 🔧 Code Structure

### Main Functions:
- `fetchUserData()` - Main function to fetch data using async/await
- `displayUsers(users)` - Renders user data to the DOM
- `showLoading()` / `hideLoading()` - Manages loading states
- `showError()` / `showSuccess()` - Handles user feedback
- `reloadData()` - Clears and refetches data

### CSS Features:
- Flexbox and Grid layouts
- CSS animations and transitions
- Responsive design with media queries
- Modern gradient backgrounds
- Card-based design system

## 📊 Data Displayed

For each user, the following information is shown:
- **Name** - Full name of the user
- **Email** - Email address
- **Address** - Complete address with street, city, and zipcode
- **Username** - User's username
- **Phone** - Contact number
- **Website** - Personal website
- **Company** - Company name

## 🌟 Future Enhancements

- Search and filter functionality
- Sorting options
- User detail modal
- Data export features
- Pagination for large datasets
- Dark/Light theme toggle

## 📝 Notes

- This project demonstrates all concepts mentioned in the internship task
- Code is well-commented for educational purposes
- Follows modern JavaScript ES6+ standards
- Implements responsive design principles
- Ready for production deployment

## 🎉 Submission Details

**Task**: Task 7 - Fetch and Display Data from Public API
**Date**: [03/07/25]
**Status**: ✅ Complete
**All Requirements Met**: Yes

---

*Created as part of Web Development Internship - Task 7*
