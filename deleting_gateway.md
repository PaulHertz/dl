---

copyright:
  years: 2019
lastupdated: "2019-12-15"

keywords: direct link, configure, connection

subcollection: dl
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:DomainName: data-hd-keyref="DomainName"}
{:note: .note}
{:important: .important}
{:deprecated: .deprecated}
{:external: target="_blank" .external}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:term: .term}  
{:generic: data-hd-programlang="generic"}
{:download: .download}  

# Deleting a Direct Link gateway and attached connections

You can delete a gateway either before or after the gateway is moved to **Provisioned** state. However, keep in mind that a gateway is restricted from being deleted during **In review** and some **In progress** states.
{:shortdesc}

To delete a gateway from the Direct Link table, highlight the row of the gateway that you want to delete, then click **Delete** from the **Overflow** ![Overflow menu](images/overflow.png) menu. Alternatively, you can click **Actions > Delete** on a gateway's details page. Click **Delete** again to confirm the deletion.

If there are any virtual connections attached to the gateway, you must detach the virtual connection before deleting the gateway. To detach a virtual connection, click **Delete** ![Delete icon](images/garbage_icon.png) next to the virtual connection entry on the gateway's details page. Then click **Delete** to confirm.
{:important}
