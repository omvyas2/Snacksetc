# Snackrun - Collaborative Shopping Lists

## 🎉 Your Shopping List App is Ready!

Snackrun is a real-time collaborative shopping list app built for your 40-person team with:
- Two-tier authentication (User/Owner roles)
- Real-time collaboration via WebSocket
- 50 products in the database with fuzzy search
- Join lists with 6-character codes
- Complete feature set including favorites, comments, archiving, and more

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
3. Enter password: **ETCisGr8!** (case-sensitive)
4. Click "Login as Owner"

## ✨ Features

### For Users
- ✅ View all lists you're a member of
- ✅ Join lists using a 6-character code
- ✅ Add items from the product database (50+ products)
- ✅ Mark items as purchased with checkboxes
- ✅ Add favorite products for quick access
- ✅ Add comments/notes to items
- ✅ See who else is active on the list
- ✅ Real-time updates when others edit

### For Owners
- ✅ Everything Users can do, PLUS:
- ✅ Create new shopping lists
- ✅ Finalize lists (locks them from editing)
- ✅ Archive old lists
- ✅ Duplicate existing lists
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
- Database contains 50 products across categories
- Fuzzy search - type partial names
- Example searches: "apple", "milk", "bread"

## 🗄️ Database

The app uses PostgreSQL with these tables:
- **users**: Authentication and roles
- **lists**: Shopping lists with join codes
- **products**: 50 seeded products
- **list_items**: Items in each cart
- **favorites**: User's favorite products
- **comments**: Notes on items/lists
- **list_members**: Who's in which list
- **user_presence**: Track active users

## 🔧 Technical Stack

- **Backend**: Express.js with TypeScript
- **Database**: PostgreSQL (Neon)
- **Real-time**: WebSocket for live updates
- **Frontend**: React with Vite
- **Styling**: TailwindCSS + shadcn/ui

## 🧪 Tested Features

✅ User authentication with @illinois.edu validation
✅ Owner authentication with password
✅ Product search with 50 seeded products
✅ Invalid email/password error handling
✅ Real-time WebSocket connections

## 🚀 Next Steps

The app is fully functional! Here's what you can do:

1. **Start using it**: Login and create your first list
2. **Share join codes**: Get your team to join lists
3. **Customize products**: Add more products to the database
4. **Deploy**: Use Replit's publish feature to deploy

## 📝 Notes

- The database is already seeded with 50 products
- All backend APIs are working
- WebSocket real-time updates are active
- Frontend is connected to the real backend
- Role badges (User/Owner) appear on all pages

Enjoy your collaborative shopping list app! 🛒
