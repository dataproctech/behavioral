### **Laboratorium 10: Wzorce behawioralne (Behavioral Patterns) w programowaniu obiektowym**

---

#### **Cel laboratorium**  
Celem laboratorium jest zrozumienie i praktyczne zastosowanie **wzorów behawioralnych** w programowaniu obiektowym. Wzorce behawioralne opisują sposób komunikacji między obiektami i definiują ich współpracę. Studenci poznają pięć popularnych wzorców: **Observer**, **Strategy**, **Command**, **State** i **Chain of Responsibility**, implementując je w językach **Java** i **C++**.

---

### **Zakres tematyczny**

Laboratorium obejmuje implementację wzorców:
1. **Observer** – Powiadamianie o zmianach.  
2. **Strategy** – Dynamiczny wybór algorytmu.  
3. **Command** – Zarządzanie poleceniami.  
4. **State** – Zmiana zachowania w zależności od stanu obiektu.  
5. **Chain of Responsibility** – Przekazywanie żądań przez łańcuch obiektów.

---

### **Efekty kształcenia**

Po ukończeniu laboratorium studenci będą:
1. Rozumieć, jak implementować wzorce behawioralne w praktyce.  
2. Potrafić dynamicznie zarządzać zachowaniem obiektów w czasie działania programu.  
3. Zrozumieć, jak wzorce behawioralne wspierają organizację kodu w dużych systemach.

---

### **Przegląd wzorców behawioralnych**

1. **Observer**  
   Wzorzec, który powiadamia wiele obiektów o zmianie stanu jednego obiektu.  
   **Przykład:** System powiadomień w aplikacjach.

2. **Strategy**  
   Wzorzec umożliwiający dynamiczne wybieranie algorytmu w czasie działania programu.  
   **Przykład:** Wybór strategii sortowania danych.

3. **Command**  
   Hermetyzuje żądanie w obiekcie, co umożliwia zapisanie, cofnięcie lub przekazanie operacji.  
   **Przykład:** System "Cofnij/Ponów" w edytorach tekstu.

4. **State**  
   Pozwala obiektowi zmieniać swoje zachowanie w zależności od stanu.  
   **Przykład:** Bankomat przechodzący przez różne stany (oczekiwanie na kartę, weryfikacja PIN, wypłata gotówki).

5. **Chain of Responsibility**  
   Umożliwia przekazywanie żądania przez łańcuch obiektów, aż zostanie obsłużone.  
   **Przykład:** Obsługa zgłoszeń w systemie wsparcia technicznego.

---

### **Zadania do wykonania**

---

#### **Zadanie 1: Implementacja wzorca Observer**

**Opis:**  
Stwórz system powiadomień, w którym użytkownicy (obserwatorzy) są informowani o nowościach w aplikacji.

**Cel:**  
- Poznanie wzorca Observer.  
- Implementacja wzorca w systemie powiadomień.  

##### **Java**
```java
import ...

interface Observer {
    
}

class User implements Observer {
    

    @Override
   
}

class NotificationService {
    
}

public class Main {
    public static void main(String[] args) {
        
    }
}
```

##### **C++**
```cpp
#include ...

// Interfejs obserwatora
class Observer {

};

// Konkretna klasa obserwatora
class User : public Observer {

};

// Klasa podmiotu
class NotificationService {

};

int main() {
   
    return 0;
}
```

---

#### **Zadanie 2: Implementacja wzorca Strategy**

**Opis:**  
Stwórz system obsługujący różne strategie sortowania danych (np. sortowanie rosnące i malejące).

**Cel:**  
- Zrozumienie wzorca Strategy.  
- Dynamiczna zmiana algorytmów w czasie działania programu.

---

#### **Zadanie 3: Implementacja wzorca Command**

**Opis:**  
Zaprojektuj system obsługujący polecenia dla aplikacji (np. "Cofnij" i "Ponów").  
Dodaj rejestr działań, aby umożliwić cofanie operacji.

**Cel:**  
- Implementacja wzorca Command.  
- Umożliwienie zarządzania poleceniami użytkownika.

---

#### **Zadanie 4: Implementacja wzorca State**

**Opis:**  
Stwórz model bankomatu, który przechodzi przez różne stany:  
1. Oczekiwanie na kartę.  
2. Weryfikacja PIN-u.  
3. Wypłata gotówki.

**Cel:**  
- Nauka, jak wzorzec State pozwala zmieniać zachowanie obiektu w zależności od jego stanu.

---

#### **Zadanie 5: Implementacja wzorca Chain of Responsibility**

**Opis:**  
Zaprojektuj system obsługi zgłoszeń w centrum wsparcia technicznego, w którym zgłoszenia są przekazywane przez łańcuch obsługi (np. od konsultanta, przez kierownika, aż po dział techniczny).

**Cel:**  
- Zrozumienie, jak wzorzec Chain of Responsibility pozwala dynamicznie przypisać odpowiedzialność za obsługę żądań.

---
