# Deep Focus

The Deep Focus quest helps you stay productive by blocking all apps except the selected ones for a set amount of time, allowing you to concentrate on what matters most. It’s perfect for deep work, studying, or tackling important tasks. Plus, every time you complete one, you earn **5 coins** to use in the app!

**Example use cases:** Study for an exam, Write a report, Code a project.

## Summary

| Title         | Description                          |
|----------------|--------------------------------------|
| Reward        | 5 coins |
| Inital Focus Time | Duration of first session |
| Increment Daily By | Duration with which to increment daily |
| Goal Focus Time | maximum focus duration |


## Fields
- **Quest Title:** A unique name for your focus session
- **Instruction:** A description for your task. Markdown is supported.
- **Days:** The days when this quest can be performed
- **Auto Destroy:** Date when the quest is destroyed
- **Initial Focus Time:** The duration of the first focus session (e.g., 25 minutes)
- **Increment Daily By:** How much time is added to the focus session with each successful completion (e.g., 5 minutes). Set to 0 if no increment is desired.
- **Goal Focus Time:** The maximum focus time after which it no longer increases (e.g., 120 minutes)

## How It Works
The Deep Focus quest starts with an Initial Focus Time for your first session. Each successful completion increases the focus duration by the Increment Daily By amount, up to the Goal Focus Time. If you don’t want the focus time to increase, set Increment Daily By to 0 and make Initial Focus Time and Goal Focus Time the same.

## Use Cases

### Use Case 1: Consistent Study Sessions (No Increment)
**Goal:** Study for a fixed 30-minute session every weekday without increasing duration.

- **Quest Title:** "Study Session"
- **Instruction:** "Block distractions and study for 30 minutes. Mark as done when finished."
- **Days:** Monday, Tuesday, Wednesday, Thursday, Friday
- **Auto Destroy:** 17/06/2024
- **Initial Focus Time:** 30 minutes
- **Increment Daily By:** 0 minutes
- **Goal Focus Time:** 30 minutes

**How It Works:** You want a steady 30-minute focus session each weekday. By setting Increment Daily By to 0 and matching Initial and Goal Focus Time, the session stays at 30 minutes every time. After completing it each day, you mark it done and earn 5 coins. The quest auto-destroys next Monday, keeping your app tidy.

**Benefit:** Maintains a predictable routine without the pressure of increasing time.

### Use Case 2: Progressive Writing Project (With Increment)
**Goal:** Gradually increase focus time for writing a report over a week.

- **Quest Title:** "Writing Focus"
- **Instruction:** "Block distractions and write for the set time. Mark as done when finished."
- **Days:** Monday, Tuesday, Wednesday, Thursday, Friday
- **Auto Destroy:** 17/06/2024
- **Initial Focus Time:** 20 minutes
- **Increment Daily By:** 10 minutes
- **Goal Focus Time:** 60 minutes

**How It Works:** You start with 20 minutes on Monday. Each successful day, the focus time increases by 10 minutes (e.g., 30 minutes on Tuesday, 40 minutes on Wednesday, etc.), up to a maximum of 60 minutes. After each session, mark it done to earn 5 coins. The quest auto-destroys after 17/06/2024.

**Benefit:** Builds endurance gradually, rewarding progress with coins.

### Use Case 3: Fixed Coding Sprint (No Increment)
**Goal:** Code for a consistent 45-minute sprint on weekends without changing duration.

- **Quest Title:** "Coding Sprint"
- **Instruction:** "Block distractions and code for 45 minutes. Mark as done when finished."
- **Days:** Saturday, Sunday
- **Auto Destroy:** 17/06/2024
- **Initial Focus Time:** 45 minutes
- **Increment Daily By:** 0 minutes
- **Goal Focus Time:** 45 minutes

**How It Works:** You want to maintain a steady 45-minute coding session each weekend. By setting Increment Daily By to 0 and matching Initial and Goal Focus Time, the session stays fixed. After each weekend session, mark it done and earn 5 coins. The quest auto-destroys by 17/06/2024.

**Benefit:** Ensures consistent focus without escalation, with a rewarding payout.

## Get Started
Ready to boost your focus and earn rewards? Create your first Deep Focus quest now and watch your productivity soar!

Happy focusing! 🎉