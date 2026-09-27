# Section 3: Data Architecture

Welcome to Section 3! Here, we talk about **Data Architecture**. If a Data Engineer is a construction worker, the Data Architect is the person who draws the blueprints of the house.

## 1. What is Data Architecture?

Data Architecture is the design of the systems that hold and move your data. A good architecture ensures the system is fast, doesn't cost too much money, and doesn't break when millions of users log in.

### Conway’s Law
*“Organizations design systems that mirror their own communication structures.”* 
If your company has 3 separate teams that never talk to each other, you will probably end up building 3 separate databases that never talk to each other!

### Principles of Good Data Architecture
- **Always Architecting:** Architecture is never "finished." Technology changes, and business needs change. You must constantly improve it.
- **When Your Systems Fail:** Assume your servers *will* crash. A good architecture has a backup plan so data is not lost when a computer dies.

### Architecting for Compliance
You must follow the law! For example, **GDPR** (in Europe) says users have the "Right to be Forgotten." Your architecture must allow you to easily find and delete a specific person's data if they ask.

---

## 2. Batch vs. Streaming Architectures

This is one of the most important decisions a Data Engineer makes!

- **Batch Architecture:** Processing data in massive groups at a scheduled time.
  - *Analogy:* Doing your laundry once a week. 
  - *Pros:* Cheap and easy to build.
  - *Use Case:* Calculating total monthly sales for the CEO.

- **Streaming Architecture:** Processing data instantly, piece by piece.
  - *Analogy:* Washing a single shirt the exact second it gets dirty.
  - *Pros:* Extremely fast (real-time).
  - *Use Case:* Detecting credit card fraud while a customer is swiping their card at the store.

---

## 3. Choosing the Right Technologies

With thousands of tools available, how do you choose?

- **Build vs Buy:** Should we write the code from scratch (Build) or pay a company for a tool that already does it (Buy)? Usually, it is better to *Buy* unless your company is doing something very unique.
- **Monolith vs Modular Systems:** 
  - *Monolith:* A Swiss-Army knife. One massive tool that does everything. If one part breaks, the whole thing breaks.
  - *Modular (Microservices):* Lego blocks. Many small tools that connect. If one breaks, you just replace that one block.
- **Compute Options:**
  - *Server (EC2):* You rent the whole machine and do everything yourself.
  - *Container (Docker):* You package your code neatly so it runs anywhere.
  - *Serverless (AWS Lambda):* You just write the code, and AWS handles all the computer hardware magically behind the scenes!

---

## 4. Investigating Your Architecture on AWS

AWS has a guide called the **Well-Architected Framework**. It helps you grade your architecture based on 6 pillars:
1. **Operational Excellence:** Is it easy to monitor and fix?
2. **Security:** Is it safe from hackers?
3. **Reliability:** If a server catches on fire, does the system stay up?
4. **Performance Efficiency:** Is it fast enough?
5. **Cost Optimization:** Are we wasting money on servers we don't need?
6. **Sustainability:** Are we using too much electricity?
