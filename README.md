# Privacy-sensitive Data Categorization (PsDC)


![Link for the Submitted Paper](https://www.techrxiv.org/users/847536/articles/1239807-individual-s-data-categorization-within-the-devprivops-lifecycle)


![Data Categorization and its Relationships into PsDC.](figs/relations.png)


![Data Categorization with PsDC - Extension of Data](extension_of.md)


![Data Categorization with PsDC - Subtype of Data - Data Format](format.md)


![Data Categorization with PsDC - Subtype of Data - Data Processed](processed.md)


## Applying the Categorization to Behavioral Analysis

Here are some examples of how this categorization can be applied to behavioral analysis for individual identification:

**Behavioral Data and Individual Identification - Extension of Data**

1. Interactions and Connections:

    - Social Media Analysis:
        - Analyzing social media interactions (likes, comments, shares) to identify individuals and their social circles.
        - Tracking the evolution of relationships over time to detect changes in behavior or social influence.
    - Email Communication:
        - Analyzing email metadata (sender, recipient, subject, content) to identify communication patterns and potential relationships.
        - Using natural language processing to extract sentiment and intent from email content.

2. Surveillance:

    - Video Surveillance:
        - Using computer vision to track individuals' movements and behaviors in public spaces.
        - Analyzing facial recognition data to identify individuals and their interactions.
    - Location Tracking:
        - Monitoring individuals' location history to identify their routines and habits.
        - Analyzing location data to detect anomalies or suspicious behavior.

3. Communication:

    - Language Analysis:
        - Analyzing language patterns (word choice, syntax, semantics) to identify individuals' personality traits and cognitive styles.
        - Using sentiment analysis to detect emotional states and intentions.
    - Voice Analysis:
        - Analyzing voice patterns (pitch, tone, pace) to identify individuals and their emotional states.
        - Using speaker recognition to identify individuals based on their unique voice characteristics.

4. Shopping:

    - Purchase History Analysis:
        - Analyzing purchase history to identify individuals' preferences and habits.
        - Using market basket analysis to identify associations between products and predict future purchases.
    - Web Browsing Behavior:
        - Analyzing web browsing history to identify individuals' interests and information needs.
        - Using clickstream analysis to track users' interactions with websites and applications.

5. Skills:

    - Online Learning Platforms:
        - Analyzing users' performance on quizzes and assignments to assess their knowledge and skills.
        - Tracking users' progress over time to identify learning patterns and areas for improvement.
    - Coding Platforms:
        - Analyzing users' code submissions to evaluate their programming skills and problem-solving abilities.
        - Identifying common coding patterns and best practices.

6. Actions:

    - Clickstream Analysis:
        - Analyzing users' clickstream data to identify their navigation patterns and information seeking behavior.
        - Using heatmaps to visualize user interactions with web pages.
    - Mobile App Usage:
        - Analyzing users' app usage data to identify their preferences and habits.
        - Using app analytics to track user engagement and retention.

**Behavioral Data and Individual Identification - Data Format**

1. Plaintext/Ciphertext

    - Direct Messages: Unencrypted messages exchanged on social media platforms like WhatsApp or Facebook Messenger.
    - Encrypted Emails: Emails encrypted with PGP or other encryption methods.

2. Anonymized Data

    - Aggregated User Demographics: Data on age, gender, and location, without specific user identifiers.
    - Pseudonymized Purchase History: Purchase data where customer names are replaced with unique identifiers.

3. Metadata

    - Social Media Metadata: Timestamps, device information, and geolocation data associated with social media posts.
    - Email Metadata: Sender, recipient, subject, and timestamp of emails.


4. Web Browsing Behavior

    - Website Visits: URLs of visited websites, time spent on each site, and clickstream data.
    - Search Queries: Keywords and phrases used in search engine queries.

5. App Usage Data

    - App Installations: List of installed apps and their usage frequency.
    - In-App Actions: Specific actions taken within apps, such as purchases, likes, or comments.

6. Location Data

    - GPS Coordinates: Real-time location data from mobile devices.
    - Cell Tower Data: Information about cell towers connected to a device.

7. 8. Social Media Interactions

    - Likes, Comments, and Shares: User interactions with posts and comments.
    - Friend Connections: Social networks and connections between users.

9. Online Purchases

    - Purchase History: Products purchased, quantities, and total spending.
    - Payment Methods: Credit card information, digital wallets, and other payment methods.


**Behavioral Data and Individual Identification - Resulted of Data Processed**

(Example: Categorizing Fitness Tracker Data)

1. Health

    - Physical: Heart rate, steps, calories burned, sleep duration
    - Mental: Stress levels inferred from heart rate variability, sleep quality

2. Sensing

    - Human Sensors: Heart rate monitor, accelerometer, gyroscope
    - Environmental Sensors: GPS, barometer (for altitude), temperature sensor

3. Spatial

    - Locality: Home, work, gym
    - Relative: Near a specific location (e.g., near a gym)
    - Absolute: GPS coordinates

4. Temporal

    - Timestamp: Time of each data point
    - Interval: Duration of workouts, sleep sessions
    - Numeric: Total steps, total active minutes

5. Logical

    - True/False: Whether a workout was completed, whether sleep was restful

Identifying Individual Behavior Patterns

By categorizing data in this way, we can identify individual behavioral patterns:

    - Routine Analysis: Analyzing temporal data to identify regular workout patterns or sleep schedules.

    - Activity Recognition: Using sensor data to classify activities like walking, running, or cycling.

    - Health Trend Analysis: Tracking changes in heart rate, sleep quality, and other health metrics over time.

    - Location-Based Behavior: Analyzing location data to identify frequent locations and mobility patterns.

    - Stress Level Detection: Using heart rate variability and other physiological data to estimate stress levels.