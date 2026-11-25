# Arkitektur

AMCOS utvecklas med målet att kunna användas med olika AI-modeller och arbetsflöden. Det syntetiska mätfallet visar en avgränsad del av systemet. Modelloberoendet och den fullständiga arkitekturen ligger utanför provet.

| Del | Roll och status |
| --- | --- |
| AICOS Core | Kontroll, spårbarhet och versionsbunden evidens. Det syntetiska exemplet använder en historiskt sparad återläsning från Core. |
| OMNIA | Arbetsflöden, verktyg och överlämningar. Utvecklas separat. |
| Measurement Model | Skilda besked om uppgiftsutfall, mätbarhet och upprepbarhet. Det sparade resultatet ligger till grund för demonstrationen. |
| EAW och R3.2 | Forskningsspår för vad som kan styrkas och hur ett underlag bedöms vid en överlämning. Formell acceptans för EAW R9C återstår och R3.2:s hypoteser H1 och H2 är oavgjorda. |

Den publika demonstrationen är ett fristående, statiskt exempel. Den kan öppnas lokalt utan server, API eller konto.
