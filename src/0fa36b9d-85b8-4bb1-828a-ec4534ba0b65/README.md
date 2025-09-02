### Joomla! Power
# AbstractEvent

This class implements the base Event object used system-wide to offer orthogonality. Core objects such as Models,
Controllers, etc create such events on-the-fly and dispatch them through the application's Dispatcher (colloquially
known as the "Joomla! plugin system"). This way a suitable plugin, typically a "system" plugin, can modify the
behaviour of any internal class, providing system-wide services such as tags, content versioning, comments or even
low-level services such as the implementation of created/modified/locked behaviours, record hit counter etc.

You can create a new Event with something like this:

$event = AbstractEvent::create('onModelBeforeSomething', $myModel, $arguments);

You can access the subject object from your event Listener using $event['subject']. It is up to your listener to
determine whether it should apply its functionality against the subject.

This AbstractEvent class implements a mutable event which is allowed to change its arguments at runtime. This is
generally unadvisable. It's best to use AbstractImmutableEvent instead and constrict all your interaction to the
subject class.

| Namespace | Joomla Version |
|-----------|----------------|
| `use Joomla\CMS\Event\AbstractEvent;` | ![All](https://img.shields.io/badge/All-purple?style=flat-square) |
| `use Error/Not/For/Joomla/Three;` | ![Joomla 3](https://img.shields.io/badge/Joomla 3-blue?style=flat-square) |

> This Joomla! Power lets you seamlessly integrate and future-proof Joomla classes in your custom code.

To add this specific power to your project in JCB:

Simply use this JPK:
```
Joomla---0fa36b9d_85b8_4bb1_828a_ec4534ba0b65---Power
```
> Remember to replace the `---` with `___` to activate this Joomla! Power in your code.

### Used in [Joomla Component Builder](https://www.joomlacomponentbuilder.com) - [Source](https://git.vdm.dev/joomla/Component-Builder) - [Mirror](https://github.com/vdm-io/Joomla-Component-Builder) - [Download](https://git.vdm.dev/joomla/pkg-component-builder/releases)

---
[![Joomla Volunteer Portal](https://img.shields.io/badge/-Joomla-gold?logo=joomla)](https://volunteers.joomla.org/joomlers/1396-llewellyn-van-der-merwe "Join Llewellyn on the Joomla Volunteer Portal: Shaping the Future Together!") [![Octoleo](https://img.shields.io/badge/-Octoleo-black?logo=linux)](https://git.vdm.dev/octoleo "--quiet") [![Llewellyn](https://img.shields.io/badge/-Llewellyn-ffffff?logo=gitea)](https://git.vdm.dev/Llewellyn "Collaborate and Innovate with Llewellyn on Git: Building a Better Code Future!") [![Telegram](https://img.shields.io/badge/-Telegram-blue?logo=telegram)](https://t.me/Joomla_component_builder "Join Llewellyn and the Community on Telegram: Building Joomla Components Together!") [![Mastodon](https://img.shields.io/badge/-Mastodon-9e9eec?logo=mastodon)](https://joomla.social/@llewellyn "Connect and Engage with Llewellyn on Joomla Social: Empowering Communities, One Post at a Time!") [![X (Twitter)](https://img.shields.io/badge/-X-black?logo=x)](https://x.com/llewellynvdm "Join the Conversation with Llewellyn on X: Where Ideas Take Flight!") [![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github)](https://github.com/Llewellynvdm "Build, Innovate, and Thrive with Llewellyn on GitHub: Turning Ideas into Impact!") [![YouTube](https://img.shields.io/badge/-YouTube-ff0000?logo=youtube)](https://www.youtube.com/@OctoYou "Explore, Learn, and Create with Llewellyn on YouTube: Your Gateway to Inspiration!") [![n8n](https://img.shields.io/badge/-n8n-black?logo=n8n)](https://n8n.io/creators/octoleo "Effortless Automation and Impactful Workflows with Llewellyn on n8n!") [![Docker Hub](https://img.shields.io/badge/-Docker-grey?logo=docker)](https://hub.docker.com/u/llewellyn "Llewellyn on Docker: Containerize Your Creativity!") [![Open Collective](https://img.shields.io/badge/-Donate-green?logo=opencollective)](https://opencollective.com/joomla-component-builder "Donate towards JCB: Help Llewellyn financially so he can continue developing this great tool!") [![GPG Key](https://img.shields.io/badge/-GPG-blue?logo=gnupg)](https://git.vdm.dev/Llewellyn/gpg "Unlock Trust and Security with Llewellyn's GPG Key: Your Gateway to Verified Connections!")