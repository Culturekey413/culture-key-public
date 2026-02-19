# ⚙️ Ethical State Machine — High-Level View

The Ethical State Machine is the high-level control mechanism that helps ensure
AI behavior remains aligned with human values and safety expectations.

It provides a predictable external model for how sensitive or risky inputs are handled.

---

## Public States

- **SAFE** — normal operation  
- **REVIEW** — ambiguous or sensitive input detected  
- **BLOCKED** — clear ethical violation  
- **ESCALATE_TO_HUMAN** — requires human judgment  

---

## Scope of This View

This diagram represents the **outer behavioral layer** of the Culture Key system.

All internal elements remain private, including:

- transition thresholds  
- risk scoring logic  
- enforcement rules  
- internal safeguards  

---

## Design Purpose

The goal of this public model is **structured transparency**:

- to demonstrate predictable governance behavior  
- to clarify how risk is handled  
- to reinforce human oversight  

For detailed transition logic, see internal State Machine rules.

---

# GR ⚙️ Ethical State Machine — High-Level View

Η Ethical State Machine είναι ο μηχανισμός ελέγχου υψηλού επιπέδου που
διασφαλίζει ότι η συμπεριφορά της ΤΝ παραμένει ευθυγραμμισμένη
με τις ανθρώπινες αξίες και την ασφάλεια.

Παρέχει ένα προβλέψιμο εξωτερικό μοντέλο για τον χειρισμό ευαίσθητων
ή επικίνδυνων εισόδων.

---

## Δημόσιες Καταστάσεις

- **SAFE** — φυσιολογική λειτουργία  
- **REVIEW** — ανίχνευση ασαφούς ή ευαίσθητου περιεχομένου  
- **BLOCKED** — σαφής ηθική παραβίαση  
- **ESCALATE_TO_HUMAN** — απαιτεί ανθρώπινη κρίση  

---

## Πεδίο Παρουσίασης

Το παρόν διάγραμμα αποτυπώνει το **εξωτερικό επίπεδο συμπεριφοράς**
του Culture Key.

Τα εσωτερικά στοιχεία παραμένουν ιδιωτικά, συμπεριλαμβανομένων:

- ορίων μετάβασης  
- λογικής αξιολόγησης ρίσκου  
- κανόνων επιβολής  
- εσωτερικών μηχανισμών προστασίας  

---

## Σκοπός Σχεδίασης

Στόχος του δημόσιου μοντέλου είναι η **δομημένη διαφάνεια**:

- να δείξει προβλέψιμη συμπεριφορά governance  
- να αποσαφηνίσει τον χειρισμό ρίσκου  
- να ενισχύσει την ανθρώπινη εποπτεία
  
