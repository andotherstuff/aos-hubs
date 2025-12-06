# Triage Framework

Once an intake form comes in, we make an initial decision about where it best fits in the AOS ecosystem. This helps us direct our limited attention where it can be most helpful.

We use three primary buckets:

- **Foundry** - project-focused partnership and building
- **Lab** - exploration, convening, and collective learning
- **Studio** - people, services, and expertise

## Step 1: Is This Primarily a Person or a Project?

We start by asking:

Is this person primarily offering *skills and services*, or asking for *help with a project or idea*?

- If they're offering skills → likely **Studio**
- If they're asking for help with a project/idea → likely **Foundry** or **Lab**

Sometimes it's both. That's fine. We tag all relevant dimensions.

## Step 2: Foundry vs Lab for Projects

If it's a project or idea, we ask:

- **Is there a founder or core steward who feels accountable for it?**
- **Is there a reasonably clear goal, even if the path is fuzzy?**
- **Is there some sense of who the project is for?** (users, communities, movements)

If the answer to most of these is **yes**, we lean toward **Foundry** and propose a discovery session.

If the project is more like a **question, exploration, or early concept** without a clear steward or path, we lean toward **Lab** and consider whether it could become a topic for a working group, hackathon, or ideation popup.

### Quick reference

| Signal | Likely routing |
|--------|----------------|
| Clear founder + defined goal | Foundry |
| "I want to build X for Y" | Foundry |
| "How might we solve X?" | Lab |
| Early exploration, no clear owner | Lab |
| Research question or thesis | Lab |

## Step 3: Studio Fit for Contributors

If someone is offering skills or services, we ask:

- What domains do they work in? (product, research, design, development, infra, operations, etc.)
- Do they have constraints around visibility, safety, or time?
- Do they want to be directly matched to projects, or just be on the radar?

If there's a good values and safety fit, we create or update a contributor entry in the Studio Rolodex (see [../studio/](../studio/)).

### Contributor fit checklist

- [ ] Skills align with ecosystem needs
- [ ] Values align with open/permissionless ethos
- [ ] Safety/visibility constraints are understood
- [ ] Availability and collaboration preferences are clear
- [ ] No red flags from initial interaction

## Step 4: Edge Cases

| Situation | Approach |
|-----------|----------|
| **Too early / too vague** | Invite to a Lab convening first, revisit later |
| **Out of scope** | Point to other communities or resources better suited |
| **High-risk contexts** | Limit documentation, use secure channels (see [05-privacy-safety-guide.md](./05-privacy-safety-guide.md)) |
| **Mixed signals** | Schedule a brief discovery call to clarify |
| **Great person, unclear fit** | Add to Rolodex, stay in touch |

## Decision Tree

```
                         +------------------+
                         | New Intake Form  |
                         +--------+---------+
                                  |
                         +--------v---------+
                         | Person or Project?|
                         +--------+---------+
                                  |
         +------------------------+------------------------+
         |                        |                        |
         v                        v                        v
   +-----------+           +-----------+           +-----------+
   |  Person   |           |   Both    |           |  Project  |
   | (skills)  |           |           |           |  (idea)   |
   +-----+-----+           +-----+-----+           +-----+-----+
         |                       |                       |
         v                       v                       v
   +-----------+           Tag both,             +-----------+
   |  Studio   |           route to              | Has clear |
   |  Rolodex  |           primary fit           | steward?  |
   +-----------+                                 +-----+-----+
                                                       |
                                          +------------+------------+
                                          |                         |
                                          v                         v
                                    +-----------+            +-----------+
                                    |    Yes    |            |    No     |
                                    |  Foundry  |            |    Lab    |
                                    +-----------+            +-----------+
```

## What Triage Is Not

The goal of triage is **not** to judge worthiness. It's to be honest about where we can actually help.

We're not evaluating:
- Whether the idea is "good enough"
- Whether the person is "impressive enough"
- Whether we personally find it interesting

We're asking:
- Where can this person or project get the most value from AOS?
- Do we have the capacity and fit to support them?
- What's the most honest and helpful path forward?
