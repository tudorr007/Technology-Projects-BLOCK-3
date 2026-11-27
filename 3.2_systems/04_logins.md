# Detecting Suspicious Activity

## Objective

Learn about **detective security controls**.

---

## Step 1 – View authentication logs

```bash
sudo cat /var/log/auth.log
```

## Step 2 – Search for login attempts
```bash
grep "Failed password" /var/log/auth.log
```

## Step 3 – View recent logins
```bash
last
```

## Questions
- What information appears in authentication logs?
  usernames, login times, ip addresses and login attempts
- Why are logs important in cybersecurity?
  they help monitor activity, detect threats and investigate security problems
- What might indicate suspicious activity?
  repeated failed login attempts, unknown ip addressses


## Deliverables
Include screenshots of:
- authentication logs
- failed login search results
