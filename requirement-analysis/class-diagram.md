# 📦 Quick-library – Class Diagram & Açıklamaları

---

## 📐 UML Class Diagram (Mermaid Formatı)

```mermaid
classDiagram
    class User {
        +String userId
        +String nickname
        +String email
        +String password
        +String avatar
        +String role
    }

    class Content {
        +String contentId
        +String authorId
        +String type
        +String text
        +List~String~ tags
        +String mood
        +Date createdAt
    }

    class AIService {
        +String apiKey
        +String prompt
        +String response
        +String type
    }

    class Club {
        +String clubId
        +String name
        +String description
        +String ownerId
        +List~String~ members
        +List~Event~ events
    }

    class Event {
        +String eventId
        +String title
        +String description
        +Date datetime
        +String clubId
    }

    class Interaction {
        +String interactionId
        +String userId
        +String contentId
        +String type
        +String commentText
    }

    User --> Content : creates
    User --> Interaction : performs
    User --> Club : owns/joins
    Club --> Event : organizes
    Content --> Interaction : receives
    AIService <.. Content : generates support
