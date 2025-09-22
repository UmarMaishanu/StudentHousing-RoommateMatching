## Use Case Descriptions

### 1. Create Profile
- **Actor**: Student
- **Description**: The student creates a profile with lifestyle preferences to enable roommate matching.
- **Preconditions**: Student is registered and logged into the system.
- **Basic Flow**:
  1. Student navigates to profile creation page.
  2. Student inputs preferences (e.g., sleep schedule, cleanliness).
  3. System validates required fields and saves profile.
- **Postconditions**: Profile is created and visible based on privacy settings.
- **Exceptions**: If required fields are missing, display an error message.

### 2. Browse Potential Roommates
- **Actors**: Student, Roommate Matching Algorithm
- **Description**: The student views a list of potential roommates based on compatibility criteria.
- **Preconditions**: Student has a completed profile and set compatibility criteria.
- **Basic Flow**:
  1. Student selects "Browse Roommates" option.
  2. System retrieves matches using the matching algorithm.
  3. System displays a list with compatibility scores and profile summaries.
- **Postconditions**: Student views potential roommates.
- **Exceptions**: If no matches are found, display a message suggesting broader criteria.

### 3. Submit Joint Application
- **Actors**: Student, Housing Admin
- **Description**: A roommate group submits a joint housing application.
- **Preconditions**: Students have formed a roommate group.
- **Basic Flow**:
  1. Group leader initiates joint application.
  2. System verifies all group members’ profiles are complete.
  3. Group submits application details (e.g., preferred housing type).
  4. System notifies housing admin of the application.
- **Postconditions**: Application is submitted and pending admin review.
- **Exceptions**: If profiles are incomplete, prompt group to complete them.
