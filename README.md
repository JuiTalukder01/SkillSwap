# SkillSwap

SkillSwap is a web-based skill exchange platform that allows users to teach skills they possess and learn new skills from others through a community-driven barter system. Instead of paying for courses, users exchange knowledge, schedule learning sessions, communicate through chat, and rate each other after completing skill swaps.

## Features

### User Management
- User registration and authentication
- Login and logout functionality
- Password recovery and reset
- User profile management
- Profile updates and customization

### Skill Exchange
- Add, edit, and delete skills
- Browse available skills
- Search and discover users by skill
- Match users based on complementary skills
- Send and manage skill swap requests

### Matchmaking System
- Automatic skill matching
- Personalized recommendations
- Match discovery page
- Pending and accepted swap management

### Communication
- Real-time messaging system
- Edit and delete messages
- File sharing in chat
- Message polling and filtering
- User notifications

### Learning Sessions
- Create learning sessions
- Accept or reject session requests
- Manage scheduled sessions
- View session history

### Events & Community
- Create community events
- Join and leave events
- Event participant management
- Update and delete events

### Rating System
- Rate users after skill exchanges
- User reputation tracking
- Feedback collection

### Video Calling
- WebRTC-based calling functionality
- Call signaling support
- Peer-to-peer communication

---

## Technology Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Responsive Design

### Backend
- PHP

### Database
- MySQL / MariaDB

### Additional Technologies
- AJAX for asynchronous communication
- WebRTC for video calling

---

## Project Structure

```text
skillswap/
│
├── index.php                 # Landing page
├── login.php                 # User login
├── register.php              # User registration
├── dashboard.php             # User dashboard
├── profile.php               # User profile
│
├── discovery.php             # Skill discovery
├── matchmaking.php           # Matchmaking logic
├── matches.php               # User matches
│
├── chat.php                  # Messaging interface
├── send_message.php          # Send messages
├── get_messages.php          # Retrieve messages
├── send_file.php             # File sharing
│
├── create_session.php        # Create sessions
├── session_list.php          # Session management
│
├── create_event.php          # Create events
├── join_event.php            # Join events
├── participants.php          # Event participants
│
├── add_skill.php             # Add skills
├── edit_skill.php            # Edit skills
├── delete_skill.php          # Delete skills
│
├── notification.php          # Notifications
├── rate_user.php             # User ratings
│
├── db.php                    # Database connection
├── skillswap.sql             # Database schema
│
├── includes/
│   ├── header.php
│   └── footer.php
│
├── uploads/
├── images/
└── style.css
