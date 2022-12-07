# Install Extension

1. Go to chrome://extensions
2. Toggle on 'Developer Mode' in the upper right corner
3. Click 'Load unpacked'
4. Select the 'extension' directory in the 'Thrifty Extension Directory'
5. Pin the extension to the toolbar to use

# Run Django Server
1. Install necessary libaries (Django, Beautiful Soup, etc.)
2. Navigate to 'Thrify Search Extension' directory
3. Enter 'python manage.py runserver' in terminal
4. Server should start- quit the server with CONTROL-C

# Test
1. Choose the shopping cart extension icon, search bar should drop down.
2. Enter article of clothing, such as "leggings" or "jeans"
3. A new tab should open with search results displayed in ascending price order.

# Troubleshooting
1. Extension will show error 'Manifest version 2 is deprecated.' This error can be ignored; the extension will function normally.
2. Check 'Errors' on the chrome://extensions page or Terminal output for any errors
3. Make sure extension is refreshed after any code changes