# Formatting Snippets

## Page Layout

```html
<div style="max-width: 900px; margin: auto; background-color: white; border: 1px solid #d1d1d1; border-radius: 6px; font-family: sans-serif; padding: 32px;">
</div>
```

## Title Block (h2)

Replace the emoji with a relevant emoji 
```html
    <div style="display: flex; align-items: center; border-bottom: 1px solid #e5e7eb; padding-bottom: 16px; margin-bottom: 24px;">
        <div style="width: 96px; height: 96px; background-color: #e5e7eb; border-radius: 8px; display: flex; align-items: center; justify-content: center; font-size: 50px; color: #6b7280; flex-shrink: 0;">🗺️</div>
        <div style="margin-left: 24px;">
            <h2 style="font-size: 36px; color: #1f2937; margin: 0;">TEXT</h2>
            <p style="font-size: 18px; color: #4b5563; margin: 4px 0 0 0;">TEXT</p>
        </div>
    </div>
```

## Header 3

```html
<h3 style="font-size: 24px; color: #374151; margin-top: 0; margin-bottom: 16px;">
</h3>
```

## Side By Side Boxes

```html
<div style="display: flex; flex-wrap: wrap; margin-top: 16px;">
    <div style="flex: 1; min-width: 300px; padding: 8px;">
        <div style="border: 1px solid #e5e7eb; border-radius: 6px; padding: 16px; height: 100%;">
            <h4 style="margin-top: 0; color: #1f2937;">TITLE</h4>
            <p style="font-size: 14px; color: #4b5563; line-height: 1.6;">TEXT</p>
        </div>
    </div>
    <div style="flex: 1; min-width: 300px; padding: 8px;">
        <div style="border: 1px solid #e5e7eb; border-radius: 6px; padding: 16px; height: 100%;">
            <h4 style="margin-top: 0; color: #1f2937;">TITLE</h4>
            <p style="font-size: 14px; color: #4b5563; line-height: 1.6;">TEXT</p>
        </div>
    </div>
</div>
```

## Grey Callout Box

```html
<div style="margin-bottom: 32px; background-color: #f9fafb; padding: 24px; border-radius: 6px; border: 1px solid #e5e7eb;">
    <h3 style="font-size: 24px; color: #374151; margin-top: 0; margin-bottom: 16px;">TEXT</h3>
    <p style="color: #4b5563; line-height: 1.6;">TEXT</p>
</div>
```

## Blue Callout Box

```html
<div style="background-color: #eff6ff; border-left: 4px solid #60a5fa; border-radius: 0 4px 4px 0; padding: 16px; margin-bottom: 32px;">
    <h3 style="font-size: 20px; color: #1e40af; margin: 0 0 8px 0;">TEXT</h3>
    <p style="color: #1d4ed8; line-height: 1.6;">TEXT</p>
</div>
```

## Paragraphs

```html
<div style="margin-bottom: 32px;">
  <p style="color: #4b5563; line-height: 1.6;">TEXT</p>
</div>
```

## Lists

```html
<ul style="color: #4b5563; margin: 16px 0; padding-left: 20px; line-height: 1.8;">
</ul>
```

## Nav Buttons

```html
<div style="border-top: 1px solid #e5e7eb; padding-top: 24px; display: flex; justify-content: space-between; align-items: center;">
  <a style="background-color: #4b5563; color: #ffffff; text-decoration: none; padding: 12px 24px; border-radius: 6px; display: inline-block;" title="TEXT" href="/courses/<COURSE_ID>/pages/<PAGE-NAME>" data-course-type="wikiPages" data-published="true"> &larr; Return to Week Overview </a>
  <a style="background-color: #4b5563; color: #ffffff; text-decoration: none; padding: 12px 24px; border-radius: 6px; display: inline-block;" title="TEXT" href="/courses/<COURSE_ID>/pages/<PAGE-NAME>" data-course-type="wikiPages" data-published="true"> Continue to NEXT PAGE &rarr; </a>
</div>
```
