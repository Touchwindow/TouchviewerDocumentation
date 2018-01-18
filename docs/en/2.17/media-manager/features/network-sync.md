# Synchronisation
![](/img/sync_empty_1.png)

Touchviewer can be managed both locally and remotely. It has been designed to distribute contents on an interactive network of stations installed in different locations. All Touchviewer clients can be configured to send or receive updates manually or in a scheduled manner. The entire architecture is based on an extremely powerful synchronisation system that ensures speed and reliability in all updating tasks with and to the remote server.

### Publish configuration
![](/img/sync_publish_open_2.png)

From here you can choose the destination for publishing contents. The destination can be a PC folder or a mapped network folder, a Dropbox service storage space.

Excluding thumbnails (recommended for archives with a lot of content) speeds up the publishing process. The thumbnails will be recreated upon synchronisation with the device downloading the updates.

If you choose __DROPBOX__ cloud service, you will need to enter all the data of the account for authentication and the name of the folder found on Dropbox.

### Update configuration
![](/img/sync_update_open_6.png)

Define the source from where you want to download updates. The source can be a PC folder, a network folder (select Robocopy), a Strongspace service storage space, or a Dropbox folder.

__Caution__ updates will be downloaded to the archive that is currently open.

![](/img/sync_update_folder_7.png)

Once you have selected the source from where you wish to download updates, you can set the synchronisation method:

* _Update contents upon software start-up_  Every time you start Touchviewer, the procedure performs a check of available updates and downloads any new content or any content that has been edited in the source folder. Tick___Ask for confirmation before updating___to receive notification asking if you want to update the archive. If you answer no, the update will be requested at the next Touchviewer start-up.
* _Do not update automatically_ Requires manual updating activation via the __Update__ button.
