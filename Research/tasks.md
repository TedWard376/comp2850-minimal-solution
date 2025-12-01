# Evaluation Tasks — Week 9

## Task 1: Filter and Complete
**Scenario**: You've just finished your COMP2850 HCI lab write-up.

**Instructions**:
1. Find the task titled "Write HCI lab notes"
2. Mark it as complete
3. Verify it's marked correctly

**Success criteria**:
- Participant finds correct task within 30 seconds
- Toggle works (checkbox/button responds)
- Visual confirmation shown (strikethrough, badge, status message)

**Inclusion focus**: Keyboard access, screen reader announcement

---

## Task 2:  Keyboard Navigation
**Scenario**: You're working on a laptop without a mouse and need to navigate the app using the keyboard only.

**Instructions**:
1. Use Tab / Shift + Tab to move through the interface
2. Navigate to the task list and select task, buy milk
3. Open its options using Enter or the appropriate keyboard shortcut
4. Confirm you can access all task actions (e.g., view, edit, complete) without using a mouse

**Success criteria**:
- All interactive elements are reachable via keyboard navigation
- Focus order is logical and predictable
- No traps (user can exit any component using keyboard alone)
- Screen reader announces focus changes correctly (if in use)

**Inclusion focus**: Keyboard access, logical focus order, screen reader compatibility

---

## Task 3: Edit Task Inline
**Scenario**: You made a typo in a task title.

**Instructions**:
1. Find task "Buy milk"
2. Edit it to "Buy oat milk"
3. Save the change

**Success criteria**:
- Edit mode activates (input appears)
- Save updates the title
- Focus returns to edited task

**Inclusion focus**: Focus management, keyboard-only editing, Cancel button

---

## Task 4: Delete Completed Task
**Scenario**: You've completed "Email supervisor" and want to remove it.

**Instructions**:
1. Find task "Email supervisor"
2. Delete it
3. Confirm it's gone

**Success criteria**:
- Confirmation shown (HTMX) OR form submits (no-JS)
- Task removed from list
- Status message announced

**Inclusion focus**: Confirmation (HTMX has `hx-confirm`, no-JS has none - documented trade-off)

---

## Metrics per Task

For each task, record:
- **Time-on-task** (seconds from start to completion)
- **Success** (1 = completed, 0 = abandoned)
- **Error count** (validation errors, wrong clicks)
- **Mode** (HTMX or no-JS)
