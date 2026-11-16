# Statement of Intent — Grade 9 Algebra Diagnostic Platform

Status: **confirmed** (2026-11-16)
Origin: KHKT proposal poster "E01. AI chẩn đoán nguyên nhân học sinh không tiến bộ"

| | |
|---|---|
| **Outcome** | A web platform for Grade 9 **Algebra** that diagnoses *why* each student isn't progressing (skill gaps via knowledge tracing, error patterns, early risk warning), suggests personalized practice, and helps teachers decide **who to help and how** every week. |
| **Users** | ~500–600 Grade 9 students in 10–13 classes at one school (mobile-first, evening use, ~200 concurrent); their math teachers (desktop dashboard); **2 math teachers** own the question bank, skill tags, and error types. |
| **Data** | Mixed: skill-tagged quizzes done on the platform + imported scores (Excel / VnEdu / SMAS / paper tests). |
| **Why now / timeline** | 3 junior university devs, **~3 months build**, go-live ~Feb–Mar 2027, real use for one semester leading into *thi vào lớp 10*. |
| **Success** | Teachers use warnings weekly; **≥70% of students practice weekly**; high-risk students who did the suggested practice **improve mock-exam (điểm thi thử) Algebra scores more** than comparable students who didn't. |
| **Constraint** | Junior team, first big project → familiar, simple stack: Spring Boot + PostgreSQL + React, small Python service for knowledge tracing (BKT + rule-based error tagging, no deep learning). Must be extensible to Geometry, more grades, and lessons later. |
| **Out of scope (V1)** | Geometry, other grades/subjects, video lessons, parent accounts, deep-learning models, native mobile app, multi-school deployment. |
