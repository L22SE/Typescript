

## EX 1
```typescript
export type profileType = {
  name: string;
  email: string;
};
const [profile, setProfile] = useState<profileType[]>([]);
```
## EX 2
```typescript
function sum(a:number,b:number){
  const sum = a+b;
  return `${a} plus ${b} sum= ${sum}`;
}
```

## EX 3 Tuple
```typescript
let tuple :[type..][];
tuple = [[typeValue],[typeValue]];
```

## EX 4 interface
```typescript
interface information {
  name:string,
  addr:string,
  num:number
}
```
## EX 5 interface extends
```typescript
interface information {
  name:string,
  addr:string,
  num:number
}

interface profile extends information{
  hobby:string,
  profile-color: 'red'|'blue'
}

const My : profile ={
  name:'lee',
   profile-color: 'red'
}

```

