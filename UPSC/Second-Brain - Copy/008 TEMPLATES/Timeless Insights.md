---
tags: out/Newsletter
---
<% await tp.file.move("/009 SHIPPED/" + tp.file.title) %>
# To-Do
- [ ] Capture Notes & Ideas
- [ ] Write a Newsletter
- [ ] Edit Newsletter
- [ ] Copy to Substack
- [ ] Review & Publish
---

Title::
Publish Date::

---
# Share Your Best Work of The Week
- 


----
# Share The Best Links You Have Found This Week

```dataview
list
WHERE file.ctime > date(today) - dur(7 days) AND !contains(file.path, "007 REFLECT")
```


---
# Share a Visual of The Week
- 
---
# Quote of The Week
- 
