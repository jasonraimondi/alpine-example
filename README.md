# Test Alpine

The Error:

<img width="982" alt="Screen Shot 2022-01-18 at 11 39 46 PM" src="https://user-images.githubusercontent.com/5787967/150085650-3700697a-9a9e-4825-be28-a224dadcd50c.png">

#### How to replicate the error

1. Start on the `working-0.5.4` branch

2. `pnpm install && pnpm build`

3. In `style.scss` note the import line:
<img width="326" alt="Screen Shot 2022-01-18 at 11 43 22 PM" src="https://user-images.githubusercontent.com/5787967/150086148-2880a544-0d87-4166-8dad-3cec7521430e.png">

<img width="300" alt="Screen Shot 2022-01-18 at 11 34 43 PM" src="https://user-images.githubusercontent.com/5787967/150085704-c9ccfc42-869f-4a69-bc7d-762bb8958e0d.png">

4. Change to the `broken-1.0.0` branch

5. `pnpm install && pnpm build`

6. In `style.scss` note the import line:
<img width="498" alt="Screen Shot 2022-01-18 at 11 42 53 PM" src="https://user-images.githubusercontent.com/5787967/150086215-4a2e4d89-e805-4249-8fc5-d59de4c07b3f.png">

<img width="331" alt="Screen Shot 2022-01-18 at 11 33 12 PM" src="https://user-images.githubusercontent.com/5787967/150085714-162c3ca5-fb8a-420a-9e75-8d1060b56521.png">

7. You can see the PR that I have showing the diff between the two branches.

8. Why does the 1.0.0 branch fail!? I dont understand. It has to be something stupid I am missing.
