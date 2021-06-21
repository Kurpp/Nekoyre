```ts
import Programmer from '../Hobbies/Programming'

export class Neko extends Programmer {
    constructor() {
      super({
         languages: ['Typescript', 'Python', 'Javascript (Node)']
      });
    };
    
    private static sleep(time: number) {
        return new Promise((resolve) => setTimeout(resolve, time));
    }
    
    public static Username: string = 'Neko'
    public static Age: number = 13;
    public static Discord: string = 'neko#0420';
    public static Projects: object = { 'Psyber': 'A Discord bot using the discord.js lib' };
    public static ToLearn: Array<string> = ['Js (Web Dev)', 'Lua', 'Advanced CSS'];
    
    public static async code() {
        await sleep(60000 * 60)
        return 'string in a string... Stringception'
    }
};
```
