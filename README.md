# Knygų rezervacijos aplikacija

Ši aplikacija leidžia vartotojams rezervuoti knygas bei administruoti knygų duomenų bazę.

## Technologijos:
- **Back-end**: Java (Spring Boot)
- **Front-end**: HTML, CSS, JavaScript
- **Duomenų bazė**: MySQL (MariaDB)
- **Autentifikacija**: Spring Security

## Diegimo instrukcijos:

1. **Duomenų bazės paruošimas**:
   - Importuokite `database.sql` failą į MySQL/MariaDB.

2. **Aplikacijos paleidimas**:
   - Užtikrinkite, kad JDK 17+ ir Maven yra įdiegti.
   - Vykdykite komandą:
     ```sh
     mvn spring-boot:run
     ```

3. **Prisijungimas prie administracinės dalies**:
   - **Administratorius**: `admin@example.com / admin123`
   - **Skaitytojas**: `user@example.com / user123`

## Funkcionalumas:
- **Administratorius**:
  - Pridėti, redaguoti ir trinti knygas bei kategorijas.

- **Skaitytojas**:
  - Ieškoti knygų ir jas rezervuoti.
  - Pridėti knygas į mėgstamų sąrašą.

Aplikacija sukurta pagal **MVC architektūrą** ir taikant **objektinio programavimo principus**.
