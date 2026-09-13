# Privacy

FiTech Log Analyzer uses a derived Device Code for limited-use activation. Online activation sends the derived Device Code, app version, and license-format information to the activation service. The service stores a one-way hash of that Device Code rather than the underlying Windows MachineGuid.

The application does not continuously monitor the user's vehicle, files, or computer.

Feedback is transmitted only when the user explicitly clicks **Submit Feedback Online**. Standard technical context may include the license ID, derived Device Code, app/Windows version, selected EFI/handheld, current tab, CSV filename, sample count, and current diagnostic context.

A screenshot is optional. The currently loaded FiTech CSV and vehicle/profile information are OFF by default and are included only when the user explicitly chooses them.

A local feedback ZIP/email fallback remains available. Feedback and support contact: **netwarker@gmail.com**.
