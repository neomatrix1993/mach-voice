# Mach dictation examples

These examples show how Refined mode can turn natural speech into ready-to-use
writing. Exact wording and punctuation can vary with your speech, selected app,
language, tone, dictionary, and Mach version. Review important output before
sending or publishing it.

## A request stays a request

Use Mach to clean a request without asking it to invent the answer.

**You say**

> can you give me three ideas for improving onboarding

**Mach writes**

> Can you give me three ideas for improving onboarding?

## Action items inside an email

**You say**

> hi everyone action items alice will update the mockups bob will review the API
> and carol will schedule the customer call thanks jordan

**Mach writes**

```text
Hi everyone,

Action items:
- Alice will update the mockups
- Bob will review the API
- Carol will schedule the customer call

Thanks,
Jordan
```

Tip: name each owner and action so Mach can separate the items.

## A numbered priority list

**You say**

> the top priorities are number one fix the login bug number two review the
> analytics dashboard and number three call the design agency

**Mach writes**

```text
The top priorities are:
1. Fix the login bug
2. Review the analytics dashboard
3. Call the design agency
```

Tip: say “number one, number two” when order matters.

## A nested project plan

**You say**

> project plan has two areas engineering with API and database and design with
> onboarding and settings

**Mach writes**

```text
Project plan has two areas:
- Engineering
  - API
  - Database
- Design
  - Onboarding
  - Settings
```

Tip: name the groups and their items so Mach can preserve the hierarchy.

## Reference a file in VS Code

**You say**

> use session dot t s as context to debug the login flow

**Mach writes**

> Use #file:session.ts as context to debug the login flow.

Tip: say the filename and extension. Mach can apply app-aware filename syntax.

## Reference a nested path in Cursor

**You say**

> check services slash billing dot p y before changing the retry logic

**Mach writes**

> Check @services/billing.py before changing the retry logic.

Tip: say “slash” and “dot” for paths and extensions.

## Spanish and English together

Select Multilingual mode before naturally switching languages.

**You say**

> Por favor mueve la reunión to three PM porque el cliente is still reviewing
> the proposal

**Mach writes**

> Por favor, mueve la reunión to 3 PM porque el cliente is still reviewing the
> proposal.

## Hindi written as Hinglish

Select Multilingual mode and enable Latin output for Hindi.

**You say**

> कल client meeting को three PM पर reschedule कर देना because Rahul is unavailable

**Mach writes**

> Kal client meeting ko three PM par reschedule kar dena because Rahul is
> unavailable.

## Japanese written as Romaji

Select Multilingual mode and enable Latin output for Japanese.

**You say**

> 明日の client meeting を午後3時に変更して then send everyone the updated invite

**Mach writes**

> Ashita no client meeting wo gogo 3ji ni henkoshite then send everyone the
> updated invite

Romaji spelling and punctuation can vary slightly.

## Exact punctuation and a byline

**You say**

> quote breaking news unquote colon the new Opus model beats Fable 5 at half the
> price new paragraph em dash Anthropic

**Mach writes**

```text
“Breaking news”: The new Opus model beats Fable 5 at half the price.

— Anthropic
```

Use explicit spoken commands when exact punctuation or layout matters.

## Learn more

- [Dictation guide](dictation.md)
- [Supported languages](languages.md)
- [Voice dictation for developers](https://usemach.app/use-cases/developers)
- [More examples on usemach.app](https://usemach.app/blog/mach-dictation-examples)
