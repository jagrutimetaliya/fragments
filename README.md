# 25 - Fragments
Render React frangement components 
```
           {
                items.map(item => (
                <React.Fragment key={item.id}>
                    <h1>Title </h1>
                    <p>{item.title}</p>
                </React.Fragment>
                ))
            }
 ```

Short hand syntext to react component => Distavantage : You can not pass key to the elements

```
 <>
            <td>JAgruti </td>
            <td>Metaliya </td>
        </>

        ```