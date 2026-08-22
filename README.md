# health-information

Health Information for Alexander Ferrari Miller

## Purpose

> "What do I know about my health?"

This repository is the authoritative reference for my personal health information and the home of the authoritative Daily Health Log. It contains diagnoses, medications, providers, medical history, laboratory results, measurements, visit summaries, daily health observations, and other health information.

The repository is intended to:

1. Maintain a complete and accurate medical history.

2. Organize health information in a consistent, searchable format.

3. Preserve historical information without overwriting previous records.

4. Support preparation of summaries for physicians and other healthcare providers.

5. Maintain `health-log.md` as the authoritative Daily Health Log.

## Repository Structure

### README.md

Overview of the repository, its purpose, organization, and documentation standards.

### conditions.md

Diagnoses, allergies, surgeries, chronic conditions, and other long-term medical history.

### medications.md

Current and historical medications, including dosage, schedule, start and stop dates, indication, and significant medication changes.

### providers.md

Healthcare providers, pharmacies, clinics, hospitals, and contact information.

### visits.md

Chronological summaries of office visits, specialist consultations, emergency room visits, hospitalizations, physician recommendations, and follow-up plans.

### labs.md

Laboratory results, imaging studies, pathology reports, and physician interpretations.

### measurements.csv

Structured recurring measurements such as blood glucose, blood pressure, pulse, oxygen saturation, temperature, weight, and other numerical data suitable for analysis and graphing.

### health-routine.yaml

Defines the expected health routine and the conventions used to record daily health information.

### meds.yaml

Structured current medication schedule and medication details.

### health-log.md

The authoritative Daily Health Log. It records what actually happened, including previous-night medications, sleep, alcohol, diet, measurements, medications, and relevant notes.

## Daily Health Log Standard

A dated Daily Health Log entry uses an overnight-to-day boundary: the previous night's medications, sleep, and alcohol are included in the following calendar day's entry. The entry then continues with that day's morning measurements and medications, diet, alcohol, later medications, and relevant notes.

### Previous Night's Medications

Record each scheduled nighttime medication with its dosage and actual status. Do not infer that a medication was taken unless it was reported as taken.

### Sleep

Record bedtime, wake time, duration or time in bed, and relevant sleep notes when known.

### Morning Medications

Record each scheduled morning medication with its dosage and actual status. Add notes only when clinically or operationally significant, such as:

- Last tablet taken

- Refill ordered

- Medication unavailable

- Dose changed

- Medication held on physician instructions

### Measurements

Record measurements in the following order:

1. Blood Glucose (if recorded)

2. Blood Pressure

3. Pulse

4. Oxygen Saturation

5. Pulse (Oximeter)

6. Temperature

7. Weight

### Diet and Alcohol

Record diet and alcohol explicitly. "Not recorded" is different from "none" or zero consumption.

### Notes

Use this section for unusual events, symptoms, physician instructions, medication changes, appointments, or other observations that may be important when reviewing the log later.

## Design Principles

- Record facts accurately and objectively.

- Keep information chronological.

- Separate structured data from narrative notes whenever practical.

- Preserve historical information rather than replacing it.

- Maintain consistency so reports can be prepared efficiently for healthcare providers.
