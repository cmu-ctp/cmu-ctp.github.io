# Adding a person

Create a new `*.md` in `_people` with a unique name for you. Then fill it with the following content.

```md
---
name: ...
website: ...
image: /assets/people/<FirstLast>.jpg
section: Student | Staff | Student
subtitle: PHD Student | Director | etc.
advisors:
    - AdvisorFirstName AdvisorLastName
---

Fun fact.
```

Use one of these for section:
- Faculty
- Staff
- Student

Add add a picture, add it to [the assets directory](../assets/people) with around `400x400` pixels as a JPEG image.  The height and width of the image should be equal, so it is a square.

Once someone leaves the group, add `alumni_since: XXXX` to make them as alumni.

Please send a pull request with the changes and an admin will merge it. 
