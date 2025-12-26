# Battle Task - Gamified Productivity Tracker

Transform your daily tasks and goals into an epic RPG battle system where productivity becomes an adventure.

## Overview

Battle Task is a unique productivity application that combines task management with RPG game mechanics. Complete real-world tasks to gain battle points and engage in weekly battles against an intelligent AI opponent that learns and adapts to your performance.

## Key Features

### 🎮 Battle System
- **Weekly Battles**: Your task completion translates into battle points used in strategic turn-based combat
- **Evolving AI Opponent**: Intelligent adversary that learns from your patterns and adapts strategies
- **Equipment System**: Unlock and equip weapons, armor, and special items through consistent performance
- **Path Selection**: Choose between Loyalist (disciplined) or Chaos (aggressive) battle paths
- **Real-time Competition**: Opponent completes tasks throughout the week in background

### 📊 Task & Goal Management
- **Flexible Task Types**: Daily, weekly, and custom frequency tasks
- **Goal Linking**: Connect tasks to personal goals and professional projects
- **Goal Tagging**: Categorize goals (Customer, Efficiency, Growth, Sustainability, etc.)
- **Document Management**: Create and track documents with descriptions
- **Custom Task Types**: Define your own task categories that persist for future use

### 🏆 Progression System
- **Ranking System**: Progress from Aspirant → Initiate → Dedicated → Veteran → Elite
- **Streak Tracking**: Build multi-week streaks for bonus rewards
- **Battle Archives**: Complete history of all battles with detailed action logs
- **Equipment Discovery**: Find new weapons and gear by defeating opponents
- **Evolution Mechanics**: Opponent grows stronger as you improve

### 🤖 Intelligent Features
- **Adaptive Difficulty**: AI adjusts based on your performance (60% to 95% completion rates)
- **Learning System**: Opponent tracks your patterns and develops counter-strategies
- **Strategic Advantages**: AI can batch complete tasks and optimize timing
- **Background Activity**: Realistic opponent progress even when app is closed
- **Persistent Notifications**: Stay updated on battle countdown and opponent progress

### 📈 Analytics & Reviews
- **Battle Statistics**: Win/loss/draw records with detailed breakdowns
- **Progress Tracking**: Monitor completion rates and performance trends
- **Mid-Year Reviews**: Comprehensive progress assessments
- **Year-End Reviews**: Annual achievement summaries
- **Equipment Inventory**: Track all discovered weapons and gear

## Technical Details

### Built With
- **Framework**: Flutter 3.10.1+
- **Language**: Dart
- **Storage**: FlutterSecureStorage for encrypted local data
- **Architecture**: Clean separation of models, services, and UI components

### Project Structure
```
lib/
├── models/          # Data models (Battle, Equipment, Goals, Tasks)
├── screens/         # UI screens and pages
│   ├── personal/    # Personal mode features
│   └── activity/    # Task and goal management
├── services/        # Business logic and utilities
└── database/        # Local storage and persistence
```

### Key Components
- **Battle System**: Turn-based combat with equipment, procs, and strategic moves
- **Task Engine**: Flexible scheduling with custom frequencies
- **Evolution System**: Progressive difficulty scaling
- **Archive System**: Complete battle history with action logs
- **Notification Service**: Background updates and persistent notifications

## Privacy & Data

All user data is stored locally on device using encrypted storage. No personal information is transmitted to external servers. See [PRIVACY_POLICY.md](PRIVACY_POLICY.md) for complete details.

## Version History

**Version 1.0.0**
- Initial release
- Complete battle system with equipment
- Evolving AI opponent with learning capabilities
- Task and goal management
- Archive system with detailed logging
- Rank progression and achievements

## Support

For issues, questions, or feature requests, please refer to the documentation files or create an issue in the repository.

## License

This is a private project. All rights reserved.

## Acknowledgments

Built with Flutter and designed to make productivity engaging through gamification mechanics inspired by RPG battle systems.
