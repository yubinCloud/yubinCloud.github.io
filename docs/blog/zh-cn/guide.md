# guide test

```python
from fastapi import FastAPI

app = FastAPI()

@app.get()
async def get_name():
    return 'yubin'
```
