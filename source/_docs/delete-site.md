---
title: Deleting a Site on Pantheon
description: Information on removing a Drupal or WordPress site from Pantheon.
tags: [manage]
categories: []
---
At some point, you may need or want to delete one of your sites on Pantheon. The number of free sites you can create is increased after a free site is deleted, or after it has converted to a paid plan.

<div class="alert alert-danger" role="alert">
<h4 class="info">Warning</h4>
<p>This action is permanent and irreversible. Export any needed content, code, or files from the site before starting this operation.</p>
<p markdown="1">Before deleting a site, you must downgrade the site plan to Sandbox level. See [Manage Site Plans](/docs/site-plan/) for more information.</p>
</div>

## Delete a Site Using the Pantheon Site Dashboard
1. Select **Settings** > **Delete Site**.
2. Click the **Delete Site** button.

  ![Site Dashboard Operations Delete Site](/source/docs/assets/images/dashboard/delete-site.png)

3. Enter the site title; this ensures you're aware of the site you're deleting.
4. Click **Delete**.

  ![Site Dashboard Operations Delete Site Confirm](/source/docs/assets/images/dashboard/delete-site-confirm.png)

## Delete a Site From the Organization Dashboard

1. Select the checkbox next to the site you want to delete.
2. Click **Operations**, and select **Delete Site**.

  ![Organization Dashboard Operations Delete Site](/source/docs/assets/images/dashboard/org-delete-site.png)

3. Type **Delete**.
4. Click **Delete Site(s)**.

  ![Organization Dashboard Operations Delete Site Confirm](/source/docs/assets/images/dashboard/org-delete-site-confirm.png)


## Delete a Site with Terminus
Run the following [Terminus](/docs/terminus/) command:
`terminus site:delete <site>`

<div class="alert alert-info" role="alert">
<h4 class="info">Note</h4>
<p>Replace <code>&lt;site&gt;</code> with your site name. You can see a list of all your sites by running <code>terminus site:list</code>.</p></div>

  ![Delete Site via Terminus](/source/docs/assets/images/delete-site-terminus.png)
