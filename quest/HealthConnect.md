# Health Connect Quest

The Health Connect Quest helps you stay on top of your fitness goals by connecting to your fitness apps or devices via the Health Connect API. It tracks activities like steps, calories, distance, sleep, and water intake, making it easy to monitor and improve your health. Every time you complete one, you earn **5 coins** to use in the app!

**Example use cases:** Track daily steps, monitor sleep quality, log water intake.

## Summary

| Title         | Description                          |
|----------------|--------------------------------------|
| Reward        | 5 coins                              |
| Initial Focus Time | Duration of first session          |
| Increment Daily By | Duration with which to increment daily |
| Goal Focus Time | Maximum focus duration              |


**NOTE:**  Due to multiple restrictions, we do not support background tracking. You must open the quest manually to check if the quest is complete. If you do not do this, the quest will not be marked as complete.

**NOTE:** BlankPhone does not support tracking data from fitness devices like smart bands, smartphones, or in-phone sensors. We only read data saved in Health Connect. Therefore, you need to connect your fitness app, such as Samsung Health, to Health Connect in order to use it.

**Health Connect:** Health Connect is a platform by Google that securely stores and syncs health and fitness data from various apps. It allows different health and fitness apps to share data in a unified way while giving users control over their privacy and permissions. [Read more about health connect](https://health.google/health-connect-android/)


## Fields
- **Quest Title:** A unique name for your fitness goal
- **Instruction:** A description for your task. Markdown is supported.
- **Days:** The days when this quest can be performed
- **Auto Destroy:** Date when the quest is destroyed
- **Activity Type:** The type of activity to track (supports steps, calories, distance, sleep, water intake)
- **Initial Count:** The starting target value for the activity (e.g., 5,000 steps)
- **Increment Daily By:** How much the target increases with each successful completion (e.g., 500 steps). Set to 0 if no increment is desired.
- **Goal:** The maximum target value after which it no longer increases (e.g., 15,000 steps)

## How It Works
The Health Connect Quest starts with an Initial Count as your first target. Each successful day, the target increases by the Increment Daily By amount, up to the Goal. If you don’t want the target to increase, set Increment Daily By to 0 and make Initial Count and Goal the same. The quest uses the Health Connect API to automatically track your activity from connected fitness apps or devices.

## Use Cases

### Use Case 1: Consistent Step Goal (No Increment)
**Goal:** Walk 10,000 steps every weekday without increasing the target.

- **Quest Title:** "Daily Steps"
- **Instruction:** "Use Health Connect to track 10,000 steps and mark as done when achieved."
- **Days:** Monday, Tuesday, Wednesday, Thursday, Friday
- **Auto Destroy:** 17/12/2024
- **Activity Type:** Steps
- **Initial Count:** 10,000 steps
- **Increment Daily By:** 0 steps
- **Goal:** 10,000 steps

**How It Works:** You want to maintain a steady 10,000-step goal each weekday. By setting Increment Daily By to 0 and matching Initial Count and Goal, the target stays fixed. The Health Connect API tracks your steps, and once you hit 10,000, you mark the quest done and earn 5 coins. The quest auto-destroys by 17/12/2024.

**Benefit:** Keeps a predictable fitness routine without escalation, with a rewarding payout.

### Use Case 2: Progressive Calorie Burn (With Increment)
**Goal:** Gradually increase calorie burn over a week for better fitness.

- **Quest Title:** "Burn Calories"
- **Instruction:** "Use Health Connect to track calories burned and mark as done when achieved."
- **Days:** Monday, Tuesday, Wednesday, Thursday, Friday
- **Auto Destroy:** 17/12/2024
- **Activity Type:** Calories
- **Initial Count:** 200 calories
- **Increment Daily By:** 50 calories
- **Goal:** 500 calories

**How It Works:** You start with a 200-calorie target on Monday. Each successful day, the target increases by 50 calories (e.g., 250 calories on Tuesday, 300 calories on Wednesday, etc.), up to a maximum of 500 calories. The Health Connect API tracks your activity, and once you meet the target, you mark it done to earn 5 coins. The quest auto-destroys after 17/12/2024.

**Benefit:** Builds fitness gradually, rewarding progress with coins.

### Use Case 3: Fixed Sleep Tracking (No Increment)
**Goal:** Ensure 8 hours of sleep each weekend night without changing the target.

- **Quest Title:** "Quality Sleep"
- **Instruction:** "Use Health Connect to track 8 hours of sleep and mark as done when achieved."
- **Days:** Saturday, Sunday
- **Auto Destroy:** 17/12/2024
- **Activity Type:** Sleep
- **Initial Count:** 8 hours
- **Increment Daily By:** 0 hours
- **Goal:** 8 hours

**How It Works:** You want to maintain a consistent 8-hour sleep goal each weekend. By setting Increment Daily By to 0 and matching Initial Count and Goal, the target stays fixed. The Health Connect API monitors your sleep, and once you achieve 8 hours, you mark the quest done and earn 5 coins. The quest auto-destroys by 17/12/2024.

**Benefit:** Ensures consistent sleep habits without escalation, with a rewarding payout.

## Get Started
Ready to boost your health and earn rewards? Create your first Health Connect Quest now and watch your fitness improve!

Happy tracking! 🎉