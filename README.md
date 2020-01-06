# Status Design

This is the repo where we co-ordinate design bounties and submissions for the Status ecosystem.

## Design projects
Every project is different, the table below shows a rough distinction between project types, their related effort and process.


| Type | Size | Example | Tech review | Design review | Design > Dev | Dev > Design
| -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| New feature     | XL     | Teller Network / TTT / Stickermarket / DApp store | x | x | x | x |
| Improvement isolated UI component |S | Additional message status | | | x | x | 
| Improvement contextual UI component |M | Snackbar | x | x | x | x | 
| Improvement isolated flow |L | Onboarding | x | x| x | x | 
| Improvement across touchpoints |XL| Profile settings / Navigation | x | x | x | x | 

    Ball park legend: S - hours, M - day, L - few days, XL - weeks
    
    Note 
    * Design is never done. 
    * A design project follows the same tradeoff as any other. There is no magic. https://fastgood.cheap/


## Design process
Design process is iterative and differs depending on the design ask. The  process outlined below describes the most common process within Status.


1. Janitor creates a design epic and story(-ies) in pivotal; including order of use cases to be covered.
1. Designer works on concept designs in [Figma](https://www.figma.com/file/cb4p8AxLtTF3q1L6JYDnKN15/Index?node-id=22%3A0).
1. Designer collects feedback from design team, and others when relevant, on concepts. Either 1:1, in a call or by tagging in Figma.
2. Janitor updates design story to use cases covered by the design

### Tech Review
5. Janitor organizes a review with the relevant technical team lead, and others if necessary. Tech reviews are needed for new features, and any M-XL sized features. 
5.  Designer updates design if needed.

### Design Review
7. Janitor organizes **Design Review**. Objective depends on state and complexity of design; Can be OK for handoff or collecting feedback in Research phase. Attendees: Designer, Developer, Nabil, Rachel, Hester.
3. Designer updates design if needed (includes coordination of final copy).
4. Janitor organizes a **Design > Dev** handoff call if needed.
1. Designer adds himself to relevant GitHub issue and shares the design files 
1. Designer continues to monitor implementation activities
5. Designer follows up to troubleshoot any questions during development and provide any additional specifications, components, screens if needed.
1. Designer reviews implementation; **Dev > Design**
1. Design story is closed in pivotal after PR is merged or further UI changes are highly unlikely.

## Brand/Marketing design
### Needs and responsibilities
Marketing team's design needs include items below, with responsible designer (Marketing or Product) added to each.
* Product landing page > Product designer
* Brandbook guided by product > Product designer
* Dedicated audience or campaign landing page > Marketing designer
* Social media assets > Marketing designer
* Post/blog headers > Marketing designer
* Occasional collatoral > Marketing designer

Assumption is that product designers only work Product landing page and brandbook. Occassionally help is needed to produce other assets. Occassionally product designers enjoy providing other assets as a welcome distraction:) (e.g. t-shirt designs).


### Way of working
To ensure consistency between product and assets we discussed the following WOW:

* Marketing team can always ask for assets, product designers can always say 'no'.
* Production files (Figma) are shared so marketing and product design can get a feeling for eachother's style.
* In case product designers are needed to provide assets (e.g. unavailability of marketing designer) marketing team provides the following requirements:
    - What is the purpose of the asset?
    - Where will it be used?
    - What are required dimensions?
    - What is the deadline?
* Product design provides a basic brandbook for each product to guide style for marketing materials. E.g. [Teller brandbook](https://www.figma.com/file/MiSADkBUtEV8ytbOzgwMgo/Teller-Brand?node-id=83%3A2033) 
    * Current [guidelines for Core](https://cdn.discordapp.com/attachments/633669891999793165/656505846498459656/Brand_Guidelines_1.pdf) need more detail (e.g. when and how wordmark and logo are (not) used and how to display app screens)
* Upcoming marketing campaigns (required assets) are [here](https://boards.status.im/b/Xi9d3DNqeGKrnZsYr/v1-launch-comms-production-list).
* When a marketing designer starts working on assets they consult brand book, provided by product design and ping in #design. 
* Final assets are shared with relevant product designer to check for any updates in the meantime (esp. regarding screens in development).
[Design review template](https://notes.status.im/vaBSUJ00RLG5lwtYzp9yPg) 

[Design checklist](https://docs.google.com/document/d/1umbtgnFjcGWwEHBCILKgGqO5H3A72eXxZrmMmhskNzs/edit?usp=sharing)



## Contact us
Join us in Status http://get.status.im/chat/public/status-design

## License

Licensed under the [Mozilla Public License v2.0](https://github.com/status-im/status-react/blob/develop/LICENSE.md)

