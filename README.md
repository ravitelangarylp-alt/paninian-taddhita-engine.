# Pāṇinian Taddhita Derivation Engine (Prāgdīvyatīya)

A Python-based computational linguistic tool that derives Sanskrit Taddhita forms based on the rules of **Pāṇini's Aṣṭādhyāyī**. 

This engine specifically focuses on the **Prāgdīvyatīya** section (Sūtras 4.1.83 to 4.1.111), handling complex derivations for Patronymics (Apatya), Clan Descendants (Gotra), and Younger Descendants (Yuvan).

## 🚀 Features

* **Logic Prioritization:** Implements Pāṇini's *Utsarga-Apavāda* (General rule vs. Exception) logic rigorously.
* **Context Sensitivity:** Asks the user specific questions to determine the correct derivation:
    * **Generational Depth:** *Apatya* vs. *Gotra* vs. *Yuvan*.
    * **Adoption Context:** Handles special cases like *Ātreya* adopted into *Bharadvāja* family.
    * **Gender:** Distinguishes between Male (*Pums*) and Female (*Strī*) ancestry where relevant.
    * **Social Context:** Differentiates forms based on *Brahmana*, *Kshatriya*, or *Angirasa* contexts.
* **Gaṇa Support:** Includes comprehensive databases for major word classes:
    * *Gargādi, Bidādi, Aśvādi, Naḍādi, Kuñjādi, Haritādi*, and more.

## 🛠️ How to Run

1.  Ensure you have **Python 3.x** installed.
2.  Clone this repository or download the `main.py` file.
3.  Run the script in your terminal:

```bash
python main.py
