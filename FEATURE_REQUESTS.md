# Feature Requests

## Kiro CLI Enhancement Requests

### 1. Auto-Save Chat History on Session End
**Priority:** High  
**Status:** Requested  
**Date:** 2025-11-20

**Description:**
Automatically save conversation history when session ends (both graceful exit and unexpected termination).

**Current Behavior:**
- User must manually type `/save` before exiting
- If session crashes or closes unexpectedly, conversation is lost
- No automatic backup mechanism

**Requested Behavior:**
- Auto-save on `/quit` command
- Auto-save on unexpected session termination
- Auto-save on crash/error
- Configurable save location
- Optional: Auto-commit to git repository

**Use Case:**
Preserve development session conversations for documentation and future reference without requiring manual intervention.

**Proposed Implementation:**
```bash
# Configuration in ~/.kiro/config.yaml
auto_save:
  enabled: true
  location: ~/current-project/chat-history/
  format: markdown
  filename_pattern: "YYYY-MM-DD-HH-mm-session.md"
  git_integration:
    enabled: true
    auto_commit: true
    commit_message: "Auto-save: Kiro session {timestamp}"
```

**Benefits:**
- No lost conversations
- Better documentation
- Reduced cognitive load on users
- Automatic project history

**Workaround:**
Created wrapper script `kiro-chat` that reminds users to save, but cannot enforce it.

---

### 2. Session Recovery
**Priority:** Medium  
**Status:** Requested  
**Date:** 2025-11-20

**Description:**
Ability to resume interrupted sessions or view recent conversation history.

**Requested Features:**
- `/history` command to view recent sessions
- `/resume` command to continue last session
- Persistent conversation cache
- Session state recovery after crash

---

### 3. Git Integration
**Priority:** Medium  
**Status:** Requested  
**Date:** 2025-11-20

**Description:**
Native git integration for automatic conversation archiving.

**Requested Features:**
- Detect git repository in current directory
- Auto-save to `chat-history/` folder
- Optional auto-commit on session end
- Configurable commit messages

---

## How to Submit These Requests

1. **AWS Support:** Contact AWS support with these feature requests
2. **GitHub Issues:** If Kiro CLI is open source, create issues
3. **Feedback:** Use AWS feedback channels
4. **Community:** Share in AWS developer forums

---

**Maintainer:** Guy Chenya  
**Project:** AI Chat UI  
**Last Updated:** 2025-11-20
