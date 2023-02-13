#### Just playing with flex property in CSS

- Specify flex property and size
```
section {
    display: flex;
    width: 1300px;
    height: 430px;
}
```

![image](https://user-images.githubusercontent.com/22846310/218365641-3c6dd0e3-1f8b-4d35-868b-1e6e1344b8c8.png)


- When pass the cursor over the image it changes the pointer, edit the individual image size and increases opacity

```
section img {
    width: 0px;
    flex-grow: 1;
    object-fit: cover;
    opacity: .8;
    transition: .5s ease;
}

section img:hover {
    cursor: crosshair;
    width: 300px;
    opacity: 1;
    filter: contrast(120%);
}
```

![image](https://user-images.githubusercontent.com/22846310/218365674-875286ac-c364-4b81-ac58-4fb5c107241c.png)


![image](https://user-images.githubusercontent.com/22846310/218365715-6933d743-7c50-457b-9e5a-001ab53e2dd4.png)
