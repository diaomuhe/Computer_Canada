# Connecting to Compute Canada

```markdown
# log from arc server
chmod 600 ccc_cloud_ghost # change the permission of the file
mv ccc_cloud_ghost .ssh # If working in the arc server, 
ssh -i .ssh/ccc_cloud_ghost -o UserKnownHostsFile=/dev/null arch@206.12.90.119
```

```markdown
# log from local window PC
- Use MobaXterm to create a shell section, set up the startup directory which contains ccc_cloud_ghost

```
# Transferring files to Computer Canada
`scp -i path_to_directory/ccc_cloud_ghost -o UserKnownHostsFile=/dev/null path_to_file/file arch@206.12.90.119:/bio/downloads`

# Once log in the server

```jsx
lsblk # list blocks
```

```jsx
df # disk filesystem
```

```jsx
ls /bio/data # data files
```

```jsx
ls /bio/databases # databases
```

```jsx
ls /bio/bin # available programs 
```

```jsx
source /bio/bin/profile
```

```jsx
echo $PATH
```

```jsx
ls -l /bio/bin/python-env/bin/ # check programs available under python
```

```jsx
source /bio/bin/python-env/bin/activate # activate python environment
```
