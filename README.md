# Daily Tracker

A comprehensive, all-in-one personal productivity web application that helps you track goals, habits, learning progress, schedule, journal entries, and much more. Built as a single HTML file with no external dependencies.

## ✨ Features

### Core Modules

- **🏠 Home Dashboard** - Daily focus, progress stats, habit overview, and learning snapshot
    
- **🎯 Goals** - Track yearly, monthly, and weekly goals with progress bars and deadlines
    
- **✅ Habits** - Build streaks, visualize weekly consistency, and track daily habits
    
- **📚 Learning** - Monitor course progress with lecture counters and platform tracking
    

### Planning & Organization

- **📅 Weekly Planner** - Day-by-day task management with priority levels (High/Medium/Low)
    
- **🕐 Schedule** - Time-block your day with duration tracking and "now" indicator
    
- **🗒️ Sticky Notes** - Color-coded notes for quick capture
    

### Reflection & Growth

- **📔 Journal** - Daily entries with mood tracking
    
- **📝 Revision Log** - Document lessons learned, mistakes, and tomorrow's goals
    
- **🔥 Motivation Vault** - Store quotes, rules, reminders, and personal missions
    

### Vision & Media

- **🌟 Vision Board** - Yearly and long-term vision statements (2026, 2027, Long-term)
    
- **🖼️ Media Vault** - Upload and organize inspirational images
    
- **🔗 Resource Library** - Save courses, books, tools, and links
    

### Analytics & Settings

- **📊 Analytics** - View habit consistency charts, learning progress, and goal completion rates
    
- **⚙️ Settings** - Customize profile, export/import data, reset all data
    

## 🚀 Quick Start

1. **Download** the `daily-tracker.html` file
    
2. **Open** in any modern web browser (Chrome, Firefox, Safari, Edge)
    
3. **Start tracking** - All data saves automatically to your browser's localStorage
    

No installation, no server, no account required!

## 📱 Usage Guide

### Navigation

- Use the **bottom navigation bar** to switch between main sections
    
- Tap **⊞ (More)** to access additional modules
    
- **Floating Action Button (FAB)** appears on relevant pages to add new items
    

### Adding Content

Each module has a `+` button to add new entries. Fill in the form and save.

### Habits

- Check the circle to mark a habit as complete for today
    
- Watch your streak grow!
    
- View 7-day history with the dot grid
    

### Goals

- Set progress percentage (0-100%)
    
- Add deadlines and notes
    
- Filter by Yearly/Monthly/Weekly tabs
    

### Data Management

- **Export** your data as JSON backup
    
- **Import** previously exported data
    
- **Reset** all data if needed
    

## ⌨️ Keyboard Shortcuts

|Key|Action|
|---|---|
|`ESC`|Close any open modal, menu, or dialog|

## 🎨 Design System

- **Typography** - DM Serif Display + DM Sans (Google Fonts)
    
- **Dark theme** - Purple/neon accent palette
    
- **Responsive** - Optimized for mobile (max-width: 480px) but works on all screen sizes
    
- **Animations** - Smooth transitions, confetti effects on habit completion
    

## 📦 Data Structure

All data is stored in `localStorage` with the prefix `kt_`:

|Key|Description|
|---|---|
|`goals`|Array of goal objects|
|`habits`|Array of habit objects with logs|
|`subjects`|Learning courses/subjects|
|`tasks`|Weekly tasks|
|`schedule`|Daily time blocks|
|`notes`|Sticky notes|
|`journal`|Journal entries|
|`revisions`|Revision logs|
|`motivation`|Quotes/rules/missions|
|`visions`|Vision board entries|
|`media`|Base64-encoded images|
|`resources`|Saved links and resources|
|`profile_name`|User's display name|
|`profile_mission`|Personal mission statement|
|`focus_YYYY-MM-DD`|Daily focus for each date|

## 🔧 Customization

### Adding Default Data

The app seeds default data on first load to demonstrate functionality. Modify the `seedDefaultData()` function to change default habits, goals, or examples.

## 🛠️ Technical Details

- **Pure HTML/CSS/JS** - No frameworks or build steps
    
- **LocalStorage** - All data stays on your device
    
- **File size** - Single ~50KB HTML file
    
- **PWA Ready** - Service worker registration placeholder included
    

## 📤 Export/Import

### Export

Go to **Settings** > **Export All Data (JSON)** - downloads a complete backup file.

### Import

Go to **Settings** > **Import Data (JSON)** - upload a previously exported file.

## 🔄 Migration Ready

The `Storage` abstraction layer uses a `kt_` prefix, making it easy to migrate to Firebase or another backend in the future.

## 🌐 Browser Support

- Chrome/Edge (latest)
    
- Firefox (latest)
    
- Safari (latest)
    
- Mobile browsers (iOS/Android)
    

## 📄 License

MIT License - Free for personal and commercial use.

---

**Start tracking your journey today!** 🚀
