## README - Transaction Isolation Levels and Anomalies

This README file provides a comparison of transaction isolation levels in PostgreSQL and MariaDB and how they relate to common transaction anomalies such as Dirty Read, Non-repeatable Reads, Phantom Reads, and Lost Update.

---

### PostgreSQL Transaction Isolation Levels

1. **READ UNCOMMITTED**:
   - Dirty Read: Happened
   - Non-repeatable Reads: Happened
   - Phantom Reads: Happened
   - Lost Update: Not Happened

2. **READ COMMITTED**:
   - Dirty Read: Not Happened
   - Non-repeatable Reads: Not Happened
   - Phantom Reads: Not Happened
   - Lost Update: Not Happened

3. **REPEATABLE READ**:
   - Dirty Read: Not Happened
   - Non-repeatable Reads: Happened
   - Phantom Reads: Not Happened
   - Lost Update: Not Happened

4. **SERIALIZABLE**:
   - Dirty Read: Not Happened
   - Non-repeatable Reads: Not Happened
   - Phantom Reads: Not Happened
   - Lost Update: Not Happened

---

### MariaDB Transaction Isolation Levels

1. **READ UNCOMMITTED**:
   - Dirty Read: Happened
   - Non-repeatable Reads: Happened
   - Phantom Reads: Happened
   - Lost Update: Not Happened

2. **READ COMMITTED**:
   - Dirty Read: Not Happened
   - Non-repeatable Reads: Not Happened
   - Phantom Reads: Not Happened
   - Lost Update: Not Happened

3. **REPEATABLE READ**:
   - Dirty Read: Not Happened
   - Non-repeatable Reads: Happened
   - Phantom Reads: Not Happened
   - Lost Update: Not Happened

4. **SERIALIZABLE**:
   - Dirty Read: Not Happened
   - Non-repeatable Reads: Not Happened
   - Phantom Reads: Not Happened
   - Lost Update: Not Happened
