# Vaxx Frontend

## Documentation Links
* [Tailwind CSS](https://tailwindcss.com/docs)
* [NextJS](https://nextjs.org/)
* [TypeScript](https://www.typescriptlang.org/docs/)
* [SASS](https://sass-lang.com/documentation)
## To Do 
======

Follow the project plan: https://docs.google.com/document/d/1TBWPG63CScyJOjs8T86K0Hzc8az5__72A2jkJANI8Z4/edit

### Objective:
The objective of this project is to gather info on local clinics distributing Vaccines, primarily focusing on 55+.

**Internally:** We are creating a way to view vaccine availability at clinics across Canada. 

**Externally:** Communicating the vaccine availability slots at clinics via twitter. 

Big idea: twitter followers see slots available 

### Overarching Product-related Goals: 

1. Display vaccine appointment availability summary (including link to book)
2. Group Regional Availabilities
3. Ask user for relevant information
    a. Phase 1: 55+
        1. Clearly displays:
            a. appointment locations
            b. dates (if applicable)
            c. separates providers with confirmed appointments from unconfirmed appointments
        2. Focus appointments at:
            a. Pharmacies
            b. Hotspot Clinics
            c. Hotspot popups
            d. Popups/Clinics for some phase 1 & phase 2 communities (ie, MHC indigenous clinic)
        3. Information collected:
            a. Age
            b. Postal Code
            c. Phase 1 & 2 community checkboxes
    b. Phase 2: Everyone
        1. Focus on appointments at
            a. Phase 1 targets
            b. Hospitals & Mass vaccination clinics
            c. Any alternative, human-inputted source
        2. Information collected:
            a. Phase 1 Information
            b. Health conditions
            c. Occupation
            d. Anything else relevant to future rollout eligibility
4. A clear UI. No muss, no fuss.
        
### Work:

[ ] Implement Multilingual Support (does Next's i18n cut it? investigate)
    a. https://nextjs.org/docs/advanced-features/i18n-routing
[ ] Investigate whether we need to support IE11 
[ ] Establish accessibility compliance goals
    - Descriptive Buttons/links (non symbolic)
    - Low stimulus colour palette 
[ ] Form: Age / Postal Code / Checklist
