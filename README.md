# RoWarner

RoWarner is a Roblox Anti-Cuss System. If you attempt to say a cuss word or bypass filter it will add a warning, if done 3 times you will be kicked, banned afterwards if you have 5 warnings.

## Settings:

1) Targetted Words:
    - In the RoWarner_Config you must add certains words a player is not allowed to say, if it is ``nil`` it will not run the Moudle.
    - Example:
```lua
return {
  Targetted = {"fuck", "shit", "anal", "sex"};
}
```
