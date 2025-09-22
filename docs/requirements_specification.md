## Stakeholder Matrix
| Stakeholder                | Interest | Influence | Needs                                   |
|----------------------------|----------|-----------|-----------------------------------------|
| Students                   | High     | High      | Easy profile setup, accurate matching   |
| Housing Admins             | High     | High      | Valid group applications, policy compliance |
| IT Admins                  | Low      | High      | System uptime, security                |
| Roommate Matching Algorithm| Medium   | Medium    | Accurate preference-based matching     |



## Functional Requirements
1. The system shall allow students to create a profile with lifestyle preferences (e.g., sleep schedule, cleanliness).
2. The system shall validate profile data for completeness and format.
3. The system shall allow students to set compatibility criteria (e.g., quiet hours, smoking preference).
4. The system shall display a list of potential roommates based on compatibility criteria.
5. The system shall calculate and display a compatibility score for each potential roommate.
6. The system shall allow students to send connection requests to other students.
7. The system shall notify students of received connection requests via email or in-app notification.
8. The system shall provide a chat feature for connected students to communicate.
9. The system shall allow students to accept or decline connection requests.
10. The system shall enable students to form roommate groups (up to 4 members).
11. The system shall allow roommate groups to submit joint housing applications.
12. The system shall validate joint applications for completeness.
13. The system shall allow students to create and sign group agreements (e.g., chore responsibilities).
14. The system shall notify housing admins of new joint applications.
15. The system shall allow housing admins to review and approve/reject joint applications.
16. The system shall log all connection requests, chats, and group activities for auditing.
17. The system shall allow students to update their profiles and preferences at any time.
18. The system shall provide a search feature to filter roommate profiles by specific criteria.

## Non-Functional Requirements
1. **Performance**: The system shall display roommate matches in under 2 seconds under normal load.
2. **Security**: All user profiles and chats shall be encrypted and comply with GDPR.
3. **Usability**: Profile creation shall be completable in 5-7 minutes with clear instructions.
4. **Reliability**: The system shall have 99.9% uptime for matching and communication features.
5. **Scalability**: The system shall handle 5,000 concurrent users during peak periods.
