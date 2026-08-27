# CampusFlow — Requirements

## 1. Problem

Campus service requests are often fragmented across different departments and communication channels. Students may not know where to submit an issue, who is responsible for it, or what its current status is.

CampusFlow provides a centralized platform where students can submit and track campus service requests while staff can manage and resolve them.

## 2. Users

### Student
- Register and log in
- Create a service request
- View their requests
- Track request status
- Add comments
- Receive notifications

### Staff
- Log in
- View assigned requests
- Accept requests
- Update request status
- Add notes/comments
- Resolve or escalate requests

### Admin
- Manage users
- Manage departments
- Manage request categories
- Assign staff
- View all requests
- Monitor system activity
- View analytics

## 3. Features

### Authentication
- Student, Staff and Admin login
- Secure password handling
- Role-based access control

### Request Management
- Create request
- View request
- Update request
- Track status
- Assign request to staff
- Resolve request
- Escalate request

### Search & Filtering
- Search requests
- Filter by category
- Filter by department
- Filter by status
- Filter by priority
- Pagination for large datasets

### Comments
- Students and staff can add comments
- Comments are linked to requests

### Notifications
- Notify users when request status changes
- Notify staff when a request is assigned

### Analytics
- Total requests
- Open requests
- Resolved requests
- Average resolution time
- Requests by category
- Requests by department

## 4. Request Lifecycle

OPEN
↓
ASSIGNED
↓
IN_PROGRESS
↓
RESOLVED
↓
CLOSED

A request may also be:

IN_PROGRESS
↓
ESCALATED
↓
IN_PROGRESS

## 5. MVP Scope

The first version of CampusFlow will focus only on the core workflow:

1. User authentication
2. Role-based access
3. Student creates a request
4. Request is stored in PostgreSQL
5. Staff can view assigned requests
6. Staff can update request status
7. Student can track request status

The MVP will NOT initially include:
- AI
- Real-time WebSockets
- Advanced analytics
- Redis
- Complex recommendation systems

These will be added after the core system works reliably.

## 6. Future Features

### Phase 2
- Priority-based request queue
- PostgreSQL indexing
- Advanced search
- Filtering and pagination

### Phase 3
- Real-time updates using WebSockets
- In-app notifications
- Staff workload management

### Phase 4
- Analytics dashboard
- Bottleneck detection
- Performance monitoring

### Phase 5
- AI-based request classification
- Automatic category prediction
- Priority recommendation

### Phase 6
- Docker
- Automated testing
- CI/CD
- Production deployment
- Load testing and performance optimization
