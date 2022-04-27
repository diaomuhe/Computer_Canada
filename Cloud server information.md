# Compute Canada

```markdown
chmod 600 ccc_cloud_ghost # change the permission of the file
```

```jsx
mv ccc_cloud_ghost .ssh # If working in the arc server, 
```

```jsx
ssh -i .ssh/ccc_cloud_ghost -o UserKnownHostsFile=/dev/null [arch@206.12.90.119](mailto:arch@206.12.90.119) 
```

```jsx
d&dYl!0n # password
```

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