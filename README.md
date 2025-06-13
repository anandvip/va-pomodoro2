README.md:
# Focus Flow - Advanced Learning Pomodoro Timer

## Purpose
A comprehensive learning-focused Pomodoro timer that transforms productivity sessions into structured learning experiences. Features topic tracking, learning reflection, cloud synchronization via Firebase, and personalized learning journey management.

## Key Features

### 🍅 Enhanced Pomodoro Timer
- Customizable work sessions (default 25 min), short breaks (5 min), and long breaks (15 min)
- Visual progress ring with smooth animations
- Smart session management with automatic break scheduling
- Browser notifications with proper permission handling

### 📚 Learning Management System
- **Topic Input Modal**: Capture learning topics before each session starts
- **Learning Reflection Modal**: Document insights and key learnings during breaks
- **Rich Text Formatting**: Bold, italic, and underline formatting for learning notes
- **In-Place Editing**: Edit historical learning entries directly with auto-save on blur

### 🎨 Advanced UI/UX
- **Theme Switching**: Light and dark mode with persistent preferences
- **Responsive Design**: Optimized for mobile, tablet, and desktop
- **Top Corner Controls**: Settings gear, theme toggle, and history access
- **Sliding Settings Panel**: Non-intrusive timer configuration

### ☁️ Cloud Synchronization
- **Firebase Integration**: Secure cloud storage for learning entries
- **Google Authentication**: Sign in to sync learning journey across devices
- **Offline Support**: Falls back to localStorage when offline or signed out
- **Real-time Sync**: Automatic synchronization of learning progress

### 📊 Progress Tracking
- **Learning History**: Chronological view of all learning sessions
- **Statistics Dashboard**: Completed sessions, total breaks, and focus time
- **Topic Organization**: Entries grouped by topic with timestamps
- **Search & Review**: Easy access to past learning insights

## Technical Implementation

### Firebase Configuration
- **Firestore Rules**: Restricts access to Google-authenticated users only
- **Authentication**: Secure Google Sign-in integration
- **Data Structure**: Optimized for learning entry storage and retrieval
- **Error Handling**: Graceful fallbacks for offline scenarios

### Security Features
- **User Isolation**: Each user only accesses their own data
- **Input Validation**: Proper sanitization of user inputs
- **Authentication Guards**: Protected routes for sensitive operations

### Browser Compatibility
- Modern ES6+ modules with Firebase v10
- Web Audio API for notification sounds
- Notification API with permission management
- Local Storage fallbacks for offline functionality

## Learning Workflow
1. **Start Session**: Enter learning topic and optional description
2. **Focus Time**: 25-minute focused learning session with progress tracking
3. **Reflect & Capture**: Document key insights and learnings during breaks
4. **Review History**: Access and edit past learning entries anytime
5. **Track Progress**: Monitor learning journey with statistics and trends

## Data Security
- Firestore security rules ensure only Google-authenticated users can read/write
- Client-side data validation and sanitization
- Secure Firebase configuration with proper access controls
- Local storage encryption for sensitive offline data
