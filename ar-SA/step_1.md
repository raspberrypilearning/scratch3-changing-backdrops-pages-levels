يمكنك استخدام الخلفيات في مشروع سكراتش لإنشاء صفحات أو مستويات مختلفة.

**تغيير البرنامج التعليمي للخلفية**: [انظر في الداخل](https://scratch.mit.edu/projects/563818117/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/563818117/?autostart=false" frameborder="0"></iframe>
</div>

انقر فوق جزء المنصة ثم **الخلفيات** لعرض الخلفيات الخاصة بمشروعك. يمكنك سحب الخلفيات لإعادة ترتيبها.

![الخلفيات بالترتيب في علامة التبويب "الخلفيات".](images/backdrops-in-order.png)

هناك العديد من الطرق `للانتقال إلى الخلفية`{:class="block3looks"}. اختر واحدًا يناسب مشروعك.

```blocks3
when [space v] key pressed
next backdrop
```

```blocks3
when stage clicked // انقر على المنصة
next backdrop
```

```blocks3
when this sprite clicked // انقر على كائن
next backdrop
```

```blocks3
when backdrop switches to [page1 v]
wait [5] seconds
next backdrop
```
