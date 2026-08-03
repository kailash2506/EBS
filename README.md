## WORKING WITH EBS

### NAME: KAILASH KUMAR S
### REGISTER NO: 212223220041
## AIM:

In this lab environment, access to AWS services and service actions might be restricted to the ones that are needed to complete the lab instructions. You might encounter errors if you attempt to access other services or perform actions beyond the ones that are described in this lab.

## OBJECTIVE:

*Create an Amazon EBS volume
*Attach and mount your volume to an EC2 instance
*Create a snapshot of your volume
*Create a new volume from your snapshot
*Attach and mount the new volume to your EC2 instance

## Illustration:

# STEP 1:
In this step, you will create and attach an Amazon EBS volume to a new Amazon EC2 instance.You will see an existing volume that is being used by the Amazon EC2 instance. This volume has a size of 8 GiB, which makes it easy to distinguish from the volume you will create next, which will be 1 GiB in size.

<img width="1902" height="865" alt="Screenshot 2026-08-03 161929" src="https://github.com/user-attachments/assets/c639c4e0-38ad-41c2-8d6a-9b3cfbadf14f" />

<img width="942" height="880" alt="image" src="https://github.com/user-attachments/assets/4b0398bc-4246-4d7f-8d22-a446d344b568" />

# STEP 2:
In this step, you will connect to the Lab EC2 instance using Session Manager.You can now attach your new volume to the Amazon EC2 instance.

<img width="1915" height="862" alt="Screenshot 2026-08-03 161618" src="https://github.com/user-attachments/assets/93db6d53-1abe-4d7b-8700-1635b3b01780" />


# STEP 3:
In this step, you will add the new volume to a Linux instance as an ext3 file system under the /mnt/data-store mount point.

<img width="954" height="878" alt="image" src="https://github.com/user-attachments/assets/d3fab652-842a-435e-b669-1595c636c512" />
<img width="1918" height="870" alt="Screenshot 2026-08-03 220939" src="https://github.com/user-attachments/assets/16d82ee1-3bb6-4303-b52b-0af3536d25c4" />
<img width="1918" height="866" alt="Screenshot 2026-08-03 220741" src="https://github.com/user-attachments/assets/a3d271c4-f9c0-4478-a841-519c3a9b01c2" />


# STEP 4:
You can create any number of point-in-time, consistent snapshots from Amazon EBS volumes at any time. Amazon EBS snapshots are stored in Amazon S3 with high durability. New Amazon EBS volumes can be created out of snapshots for cloning or restoring backups. Amazon EBS snapshots can also be easily shared among AWS users or copied over AWS regions.

<img width="954" height="878" alt="image" src="https://github.com/user-attachments/assets/e18a5014-4041-415c-935c-2b48638f30fb" />
<img width="960" height="876" alt="image" src="https://github.com/user-attachments/assets/434dec9a-b3c4-4545-ad56-f8a9d5e9611b" />

# STEP 5:
<img width="603" height="527" alt="image" src="https://github.com/user-attachments/assets/4c447805-3d63-4de5-a9e6-33ce6e4f0c2c" />

## RESULT:
Successfully created, managed, and deleted an EBS bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon EBS.
