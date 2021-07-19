

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
