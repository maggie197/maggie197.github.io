### To get the files from your Google Cloud VM
1. Install Google Cloud SDK
2. Authenticate your Google Cloud account
```
gcloud auth login
```
3. Identify the VM's External IP address:
   * Go to your Google Cloud Console and find your VM instance. The external IP address will be listed there.
4. Use gcloud to copy files: Now, from your terminal on your PC, you can use the gcloud compute scp command to copy files.
```
   gcloud compute scp --recurse your-vm-name:/var/www/html /path/to/your/local/destination --zone YOUR_VM_ZONE
```
* Replace your-vm-name with your VM instance name.
* Replace /path/to/your/local/destination with the path on your local PC where you want to store the files.
* Replace YOUR_VM_ZONE with your VM’s zone (e.g., us-central1-a).
This will download all the files from /var/www/html on your VM to your local directory.

