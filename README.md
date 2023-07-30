## README - Transaction Isolation Levels and Anomalies

This README file provides a comparison of transaction isolation levels in PostgreSQL and MariaDB and how they relate to common transaction anomalies such as Dirty Read, Non-repeatable Reads, Phantom Reads, and Lost Update.

---
<img width="1102" alt="image" src="https://github.com/danylboiko95/SQL_isolations/assets/44903844/6b3c49e0-107b-4354-a4cd-136d7a0f60e4">

### PostgreSQL Transaction Isolation Levels

1. **READ UNCOMMITTED**:
   - Allows Dirty Read: Happened
   - Allows Non-repeatable Reads: Happened
   - Allows Phantom Reads: Happened
   - Allows Lost Update: Not Happened

2. **READ COMMITTED**:
   - Allows Dirty Read: Not Happened
   - Allows Non-repeatable Reads: Not Happened
   - Allows Phantom Reads: Not Happened
   - Allows Lost Update: Not Happened

3. **REPEATABLE READ**:
   - Allows Dirty Read: Not Happened
   - Allows Non-repeatable Reads: Happened
   - Allows Phantom Reads: Not Happened
   - Allows Lost Update: Not Happened

4. **SERIALIZABLE**:
   - Allows Dirty Read: Not Happened
   - Allows Non-repeatable Reads: Not Happened
   - Allows Phantom Reads: Not Happened
   - Allows Lost Update: Not Happened

---
<img width="1099" alt="image" src="https://github.com/danylboiko95/SQL_isolations/assets/44903844/59145257-ac10-401c-8085-1564c082bb86">

### MariaDB Transaction Isolation Levels

1. **READ UNCOMMITTED**:
   - Allows Dirty Read: Happened
   - Allows Non-repeatable Reads: Happened
   - Allows Phantom Reads: Happened
   - Allows Lost Update: Not Happened

2. **READ COMMITTED**:
   - Allows Dirty Read: Not Happened
   - Allows Non-repeatable Reads: Not Happened
   - Allows Phantom Reads: Not Happened
   - Allows Lost Update: Not Happened

3. **REPEATABLE READ**:
   - Allows Dirty Read: Not Happened
   - Allows Non-repeatable Reads: Happened
   - Allows Phantom Reads: Not Happened
   - Allows Lost Update: Not Happened

4. **SERIALIZABLE**:
   - Allows Dirty Read: Not Happened
   - Allows Non-repeatable Reads: Not Happened
   - Allows Phantom Reads: Not Happened
   - Allows Lost Update: Not Happened
