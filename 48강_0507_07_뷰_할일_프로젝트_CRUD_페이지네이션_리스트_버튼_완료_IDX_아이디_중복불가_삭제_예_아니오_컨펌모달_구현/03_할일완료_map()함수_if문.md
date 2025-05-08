# 할일완료_map()함수_if문

```js    
    this.state.할일리스트.map((item)=>{
        if(item.idx===idx){
            return item.완료=true
        }
        else{
            return item       // 바꾸지 않는다
        }                            
    });
```