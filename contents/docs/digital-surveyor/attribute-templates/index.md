---
title: Attribute Templates
description: Learn how to create and configure attribute templates for feature extraction
---

# Attribute Templates

Attribute templates define what features Digital Surveyor will extract from your dataset. In this section we'll cover how to build one from scratch—if you already have a template, skip ahead to **Running Perception**.

***

### Creating New Layers

First, open the template menu and navigate to the creation page, then add layers one by one:

{% stepper %}
{% step %}
### Step 1: Access Template Menu
In **Folders & Files**, click **Upload data** → **Template**.
<figure><img src="/contents/images/image66.png" alt="Access Template Menu" width="100%"></figure>
{% endstep %}
{% step %}
### Step 2: Open Creation Page
You'll land on the template creation screen. Here you can either click **Add New Layer** or upload an existing GDB.
<figure><img src="/contents/images/image54.png" alt="Template Creation Screen" width="100%"></figure>
{% endstep %}
{% step %}
### Step 3: Add New Layer
Click **Add New Layer** (blue button). A textbox appears—this is where you name your feature.
<figure><img src="/contents/images/image43.png" alt="Add New Layer Button" width="100%"></figure>
{% endstep %}
{% step %}
### Step 4: Name Your Feature
Enter the feature name in the box, then click **+ Add** to proceed.
<figure><img src="/contents/images/image60.png" alt="Name Feature Textbox and + Add" width="100%"></figure>
{% endstep %}
{% step %}
### Step 5: Choose Feature Type
In the dropdown outlined in green, select **Feature Type**.
<figure><img src="/contents/images/image51.png" alt="Feature Type Dropdown" width="100%"></figure>
{% endstep %}
{% step %}
### Step 6: Select Specific Feature
In the adjacent dropdown, choose the specific object or linear feature from Mach9's supported list.
<figure><img src="/contents/images/image58.png" alt="Supported Features List" width="100%"></figure>
{% endstep %}
{% step %}
### Step 7: Finalize Layer
If no subattributes or rules are needed, click **Add Layer** (blue bar) to finish.
<figure><img src="/contents/images/image42.png" alt="Add Layer Confirmation" width="100%"></figure>
{% endstep %}
{% endstepper %}

***

### Template Configuration

If you need subattributes, validation, or custom rules, use the sections below:

#### Feature Types

> * **Points**: Discrete features (e.g., signs, poles)
> * **Lines**: Linear features (e.g., road markings)
> * **Polygons**: Area features (e.g., buildings)

#### Attributes

> * Define attribute name and description
> * Choose data type (text, number, date, etc.)
> * Mark required vs optional
> * Set default values

#### Validation

> * Specify value ranges
> * Enforce format requirements
> * Flag required fields
> * Add custom validation logic

***

### Best Practices

> * Use clear, descriptive layer names
> * Group related attributes logically
> * Apply validation to catch errors early
> * Include helpful descriptions for each attribute
> * Test templates on a sample dataset

***

### Template Management

After creation, manage your templates easily:

{% stepper %}
{% step %}
### 1. Edit Templates
Modify layers, feature types, or attribute rules on any existing template.
{% endstep %}
{% step %}
### 2. Duplicate Templates
Clone a template to make a similar one—saves setup time.
{% endstep %}
{% step %}
### 3. Delete Templates
Remove templates you no longer need. (Note: deletions are permanent.)
{% endstep %}
{% endstepper %}
