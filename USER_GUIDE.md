# Snackrun - Collaborative Shopping Lists

## 🎉 Your Shopping List App is Ready!

Snackrun is a real-time collaborative shopping list app built for your team with:
- Two-tier authentication (User/Owner roles)
- Real-time collaboration via WebSocket
- OpenFoodFacts products in the database with fuzzy search
- Join lists with 6-character codes

## 🔐 Authentication

### Login as User
1. Go to the login page
2. Select **"User Login"** tab
3. Enter your name
4. Enter email ending with **@illinois.edu** (required)
5. Click "Login as User"

### Login as Owner
1. Go to the login page
2. Select **"Owner Login"** tab
3. Enter password
4. Click "Login as Owner"

## ✨ Features

### For Users
- ✅ View all lists you're a member of
- ✅ Join lists using a 6-character code
- ✅ Add items from the product database
- ✅ See who else is active on the list
- ✅ Real-time updates when others edit

### For Owners
- ✅ Everything Users can do, PLUS:
- ✅ Create new shopping lists
- ✅ Finalize lists (locks them from editing)
- ✅ Archive old lists
- ✅ View final cart page

## 📋 How to Use

### Creating a List (Owners Only)
1. Click "Create New List" button
2. Enter a list name
3. A unique 6-character join code is automatically generated
4. Share the code with your team

### Joining a List
1. Click "Join List" button
2. Enter the 6-character code
3. You're now a member and can see/edit the list

### Adding Items
1. Open a list
2. Search for products using the search bar
3. Click on a product or create a custom item
4. Items appear in the cart in real-time

### Real-time Collaboration
- When anyone adds/removes/updates items, everyone sees it instantly
- Active users are shown at the top of the list
- No need to refresh - changes appear automatically

### Product Search
- Database contains almost every item you can think of, be as specific with the names
- If item not found, create a custom item


## 🧪 Tested Features

✅ User authentication with @illinois.edu validation
✅ Owner authentication with password
✅ Product search
✅ Invalid email/password error handling
✅ Real-time WebSocket connections

