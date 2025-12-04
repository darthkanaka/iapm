# Project Management System

A comprehensive project management application for creative agencies built with React.

## Features

- **Timeline View** - Horizontal scrolling timeline with tasks, events, and lists
- **Calendar View** - Month view with day cells showing all items
- **List View** - Filtered list with day grouping, search, and filtering
- **Client View** - Deep dive into clients and projects with notes, tasks, and events

### Task Management
- Status tracking: To Do, In Progress, Blocked, On Hold, Urgent
- Due date awareness with "Due Soon" and "Overdue" badges
- Assignee management
- List/checklist containers with progress tracking

### Event Management
- Attendees with permission levels
- Visibility settings: Team, Attendees Only, Private
- Edit/delete permissions based on role

### Collaboration
- Threaded notes with @mentions
- Real-time notification system
- Team member tagging in notes and replies

## Live Demo

Visit: `https://[your-username].github.io/[repo-name]/`

## Setup for GitHub Pages

1. Create a new GitHub repository
2. Upload `index.html` to the repository root
3. Go to Settings → Pages
4. Set Source to "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click Save
7. Wait 1-2 minutes for deployment
8. Access your app at the provided URL

## Local Development

Simply open `index.html` in a web browser. No build step required!

For live reloading during development, you can use any static file server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

## Technology Stack

- **React 18** - UI framework (loaded via CDN)
- **Lucide React** - Icon library
- **Babel Standalone** - JSX transformation in browser
- **Pure CSS** - No external CSS framework

## File Structure

```
/
├── index.html      # Complete application (single file)
└── README.md       # This file
```

## Future Enhancements

To add backend functionality:

1. **Supabase Integration**
   - Authentication
   - PostgreSQL database
   - Row-level security
   - Real-time subscriptions

2. **Recommended Database Schema**
   - See `TECHNICAL_SPEC.md` for complete schema

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## License

MIT License
