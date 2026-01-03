# Problem Statemnt:

Patients often forget medication timings, misunderstand prescription labels, or fail 
to follow specific instructions such as dosage, food restrictions, duration, and warning 
labels. Existing reminder applications mainly provide time-based alerts but lack the 
ability to understand and interpret medication labels or personalize reminders based 
on patient-specific instructions.
There is a need for an intelligent, label-aware medication reminder system that can 
automatically interpret prescription labels and provide accurate, context-aware reminders. 
Such a system should understand medication names, dosage schedules, intake instructions 
(before/after food), warnings, and special conditions, while adapting reminders to 
individual patient needs. Additionally, it should support conversational interaction,
allowing users to ask questions and receive clear guidance in simple language.

Proposed Solution:

We propose a Label‑Aware Medication Reminder Chatbot that:

    1.Uses openFDA Drug Label data as a trusted medical knowledge source
    2.Applies Retrieval‑Augmented Generation (RAG) for accurate Q&A
    3.Generates sample medication reminder schedules in JSON format based on dosage instructions

The chatbot acts as both:
    
    1.A Drug Information Assistant (Q&A over labels)
    2.A Reminder Plan Generator (machine‑readable schedules)