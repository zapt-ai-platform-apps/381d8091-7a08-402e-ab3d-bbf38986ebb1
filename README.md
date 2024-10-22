# Save Facts

An app to generate and save facts about planet Earth.

## User Journeys

1. **Sign In**

   - User opens the app.
   - User sees a sign-in page with the "Sign in with ZAPT" message.
   - User can sign in using email (magic link) or social providers (Google, Facebook, Apple).
   - After successful sign-in, user is redirected to the home page.

2. **Generate a Fact**

   - On the home page, the user sees an option to generate a new fact.
   - User clicks the "Generate Fact" button.
   - The app requests a new fact about planet Earth from the AI backend.
   - The generated fact is displayed in the text area.

3. **Save a Fact**

   - User can choose to save the generated fact.
   - User clicks the "Save Fact" button.
   - The fact is saved to the user's collection.
   - A confirmation message is displayed.

4. **View Saved Facts**

   - User can view a list of their saved facts.
   - The facts are displayed in a scrollable list.
   - User can read and revisit the facts.

5. **Additional Features**

   - **Generate Image**: User can generate a stunning image related to Earth by clicking "Generate Image".
   - **Convert Fact to Speech**: User can convert the displayed fact into speech by clicking "Convert Fact to Speech".
   - **Generate Article**: User can generate a markdown article about Earth by clicking "Generate Article".

6. **Sign Out**

   - User can sign out of the app.
   - User clicks the "Sign Out" button.
   - User is signed out and returned to the sign-in page.

## External API Services

- **ChatGPT**: Used to generate facts about planet Earth and markdown articles.
- **AI Image Generation**: Used to generate images related to Earth.
- **Text-to-Speech**: Used to convert facts into speech audio.
