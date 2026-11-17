# Introduction to Design Patterns with Python

## Project Overview

This project explores three foundational object-oriented design patterns:

- Factory (Creational)
- Observer (Behavioral)
- Decorator (Structural)

## Task 0: Factory — Extending a Registry

**File:** `0-factory.py`

Implemented:
- Registered Scooter using `register_kind()`.
- Created a Scooter instance through the factory.
- Extended functionality without modifying `VehicleFactory.create()`.

**Expected output:**
```text
road
rails
lane
scooter_lane
```

**Validation:**
- Execution: Passed
- Python compilation: Passed
- PEP 8: Passed


## Task 1: Observer — Adding a New Subscriber

**File:** `1-observer.py`

Implemented:
- Created SmsObserver with an update() method.
- Subscribed SMS notifications exclusively to the breaking topic.
- Preserved NewsSubject and existing observers.

**Expected output:**
```text
email:weather=rain
log:sports=goal
email:sports=goal
log:breaking=alert
email:breaking=alert
sms:breaking=alert
```

**Validation:**
- Execution: Passed
- Python compilation: Passed
- PEP 8: Passed
