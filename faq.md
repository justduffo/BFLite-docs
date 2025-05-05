---
title: ❓ FAQ
order: 90
---

# Frequently Asked Questions

Here are answers to the most commonly asked questions about the BFLite Framework.

---

### 🚀 What versions does it support?
BFLite is compatible with Unreal Engine 5.4 and above. If there is an audience for older versions, we can consider adding support for them.

---
### 💸 Does BFLite stay free?
Yes. We have no intent to make this a paid framework. It will remain free and updated based on community feedback and new ideas.

---

### ✨ Will there be new features?
Absolutely! We plan to keep updating the framework after release. We also plan on releasing premium version of existing features as well as new components you can get seperate to add on

---

### 👣 How do I add new footstep sounds?
Add new surface types in Project Settings under **Physical Surface**, create a matching physical material, and hook it up inside `FootstepTrace` in `BP_Character_Base`.

---

### 🛠 How do I create custom interactable actors?
Either use `BP_Interaction_Master` as a base or create a new actor and add the `BPI_Interaction` interface. Don’t forget to implement `OnInteract`.

---

### 🔀 Can I combine different events with the Event Maker?
Yes, you can use multiple event makers into the world to create complex scenes, a good example is the ending of the demo map

---

### ❌ What if my actor doesn’t respond to interaction?
Make sure collision is set to block the interaction trace and that `OnInteract` is implemented.

---

### 🎨 Can I fully customize the menu layout and UI?
Yes. All widgets are located in `Widgets/Menu` and are commented for easy editing.

---

### 💬 Where can I get help or share ideas?
- Join our [Discord server](https://discord.gg/K6VmuhcnQM) for support, feedback, or suggestions.
- Or contact us at support@breakboundstudios.com

---

### 📁 Are all assets provided free to use?
Yes! All assets provided with the framework are free to use in your own projects.

---

### 🔌 Can I add this framework to an existing project?
Yes, you can! However, we currently do not have an integration tutorial available — stay tuned!


---

