[Heading1] Creator Club
[Heading2] Phase 1 MVP: Platform Development Brief
Version 1.6 | October 28, 2026
[Heading2] The Business: What We Are Building and Why
Creator Club is a recurring-membership business for emerging and growing content creators, especially those who lack funding, brand access, or consistent ways to earn from their audiences.
Its core offering is access to:
[LIST] Get Funded: Creative funding competitions and grants.
[LIST] Get Paid: Monetization opportunities, brand collaborations, affiliate programs, and selective product partnerships.
[LIST] Get Connected: Access to established creators, experts, and industry connections.
Members can also access discounted shared creative services, including video editing, design, branding, and other professional resources.
The club is not a course platform or an agency representing every member.
[Heading2] Development Purpose: What Needs to Be Created
Build a mobile-first platform that supports the complete operation of Creator Club.
The platform must include:
[LIST] Public website: Competition pages and contestant profiles where visitors discover the club, explore submissions, review past winners, and register. 
[LIST] Creator portal: A private dashboard where paying members manage subscriptions, enter competitions, vote, access opportunities, attend sessions, and participate in the club community forum.
[LIST] Admin dashboard: Operational tools for authorized staff to manage content, competitions, submissions, opportunities, events, member inquiries, and community discussions.
[LIST] Super Admin dashboard: Complete control over membership plans, pricing, voting rules, eligibility, finances, admin permissions, competition verification, and approvals.
[LIST] Backend system: Payments, subscriptions, voting validation, data management, permissions, notifications, security, and reporting.
The platform must also provide a private creator community with a discussion forum, using Reddit as a functional reference for topic-based posts, threaded replies and voting on discussions. Include a separate announcements section for official club updates, an email-style notification inbox for individual messages, session registration and interest tracking, and an admin-managed opportunities page that shows public listings and relevant opportunities targeted to creator groups or individual creators.
A central part of the business is the creator-driven acquisition process:
A contestant shares their competition entry, visitors discover the competition, and eligible visitors can become paying members and vote.
[Heading2] 1. User Roles, Purposes & Permissions
[Heading3] A. Public Visitor
Why they visit
Public visitors typically arrive from a contestant's shared link, social media, advertising, or search.
They want to watch an entry, understand the prize and competition rules, see participating creators or past winners, and decide whether to join.
What they can do
[LIST] Browse published competitions.
[LIST] Browse each competition’s public gallery and individual entry pages (detailed in Section 2A).
[LIST] Watch submitted videos.
[LIST] View publicly available creator information.
[LIST] Read official rules, FAQs, prizes, and deadlines.
[LIST] Explore previous competitions and announced winners.
[LIST] Share competition and contestant URLs.
[LIST] View membership information and register or log in.
[LIST] Browse opportunities marked public on the Opportunities page (applying requires membership).
[LIST] Vote button and member access
[LIST] Show a “Vote for this contestant” button on each approved entry page while voting is open.
[LIST] If a visitor is not logged in, direct them to a page offering “Log in” and “Join,” explaining the competition’s voting eligibility requirements.
[LIST] After login or registration, return the user to the same entry page.
[LIST] Check the user’s voting eligibility before allowing them to confirm their vote. Login or registration must not automatically cast a vote.
[LIST] If the user is not eligible, explain the requirement and provide the relevant next step.
[LIST] Each eligible paid account can vote for only one creator per competition (full rules in Section 5C).
Public visitors cannot vote, submit competition entries, or access private member information without eligible membership access.
[Heading3] B. Creator / Member
Why they join
Creators join to enter funding competitions, participate in voting, discover brand and affiliate opportunities, attend sessions with established creators, and access discounted professional resources.
What they can do
[LIST] Create and manage their creator profile.
[LIST] Subscribe and manage membership and payment details.
[LIST] Submit competition entries and promote them to their audiences.
[LIST] Track submissions and past competitions.
[LIST] Vote for other contestants when eligible.
[LIST] Browse and apply for monetization opportunities.
[LIST] Register interest in proposed sessions and register for expert sessions and events.
[LIST] Access discounted creative services and tools.
[LIST] Participate in the member forum.
[LIST] Read official club announcements and receive messages in their notification center.
[LIST] Receive notifications and contact support.
[LIST] View their own final verified vote count once results have been approved and released.
Live vote counts remain hidden from all members throughout competitions.
[Heading3] C. Admin (Multiple Staff Accounts)
Why they use the platform
Admins are responsible for operating the club day to day without requiring access to sensitive business settings or complete financial information.
What they can do
Depending on their assigned permissions:
[LIST] Create and publish pages, FAQs, and announcements.
[LIST] Create competitions and manage their details.
[LIST] Review and approve submissions.
[LIST] Monitor voting activity and investigate suspicious votes.
[LIST] Manage opportunities, applications, and expert sessions.
[LIST] Maintain discounted services and tools listings.
[LIST] Moderate the community forum.
[LIST] Respond to member inquiries and support requests.
[LIST] Send approved communications.
[LIST] Record grant fulfillment after approvals.
Admins cannot independently change global policies, membership prices, staff permissions, or finalize competition winners.
[Heading3] D. Super Admin
Why they use the platform
Super Admin controls the overall business, establishes policies, approves sensitive decisions, and monitors operational and financial performance.
What they can do
[LIST] Manage membership plans, prices, and promotional access.
[LIST] Create admin accounts and assign permissions (similar to Shopify).
[LIST] Configure registration and voting eligibility.
[LIST] Approve official competition rules and tie-breaking criteria.
[LIST] Review financial reports, subscriptions, refunds, and disputes.
[LIST] Access complete member and competition reports.
[LIST] Investigate suspicious voting activity.
[LIST] Approve winners and final results.
[LIST] Control the release of private final vote counts.
[LIST] Oversee grants and prize fulfillment.
[LIST] Access audit records and sensitive platform settings.
All important administrative actions and sensitive overrides must remain traceable.
[Heading3] E. Membership Levels & Permissions
[LIST] Build three configurable paid membership levels (temporary names: Level 1, Level 2, Level 3).
[LIST] Each level has its own price, description, benefits, feature access, active status, and visibility settings.
[LIST] Only one membership level may be publicly visible at launch.
[LIST] Support active, trial/pending (if offered), failed-payment/past-due, canceled, suspended, and expired membership statuses.
[LIST] Super Admin manages membership levels, prices, and enabled tiers.
[LIST] Super Admin creates admin accounts and assigns separate permissions for viewing, creating, editing, publishing, deleting, moderating, and exporting.
[LIST] Permissions must apply by module and data sensitivity.
[LIST] Admins cannot change their own permissions or access unassigned information.
[Heading2] 2. Public Experience: Without Login
Goal: Allow people to discover competitions and creators without purchasing membership. Public competition pages and shareable links are the primary acquisition path. Browsing is open, but voting is restricted.
[Heading3] A. Competition & Contestant Pages
[LIST] Public competition pages display:
[LIST] Competition title and category.
[LIST] Prize/grant information.
[LIST] Competition brief.
[LIST] Submission and voting schedules.
[LIST] Eligibility requirements.
[LIST] Official rules and FAQs.
[LIST] A public gallery of approved contestant entries, each showing the contestant’s name, entry title and thumbnail, and linking to their individual entry page.
[LIST] Final results when published.
[LIST] Every approved contestant receives a unique, shareable entry URL.
[LIST] Each public entry page displays the contestant’s name, the approved video or Reel, the entry description, limited creator information, and a clear Join / Log in to Vote call to action.
[LIST] Public visitors can view opportunities marked public; targeted and member-only opportunities, and applying, require an eligible signed-in member.
[LIST] Visitors can watch approved entries without membership.
[LIST] Draft, pending review, rejected, and withdrawn entries must never appear publicly.
[LIST] Voting requires an eligible, signed-in member.
[LIST] Never publicly display live vote counts or rankings.
[LIST] Maintain a public archive of previous competitions, winners, verified results, and grants/prizes awarded.
[LIST] Public leaderboard and winner highlights are uploaded manually as curated images, not generated through automated rankings.
[Heading3] B. Acquisition Attribution
[LIST] Track which contestant or competition link brought a visitor to the platform.
[LIST] Track registrations and paid signups originating from those links.
[LIST] Preserve referral/source and campaign information through registration and checkout where feasible.
[LIST] Provide authorized staff with reports on:
[LIST] Visits.
[LIST] Registrations.
[LIST] Paid conversions.
[LIST] Attributable revenue.
[LIST] Performance by contestant, link, or campaign.
[LIST] No referral commission or rewards engine is required in Phase 1.
[Heading2] 3. Creator Portal: Member Actions Only
Goal: Give paying members one place to manage their membership and participate in the opportunities offered by the club.
This section describes member actions only. Staff controls are listed separately.
[Heading3] A. Account, Profile & Membership
[LIST] Sign up, verify email, log in, and reset password.
[LIST] Create and edit a profile containing:
[LIST] Name and display name.
[LIST] Creator niche/category.
[LIST] Year of birth (required; used for age-eligibility checks and never shown publicly).
[LIST] Location.
[LIST] Linked social media handles (multiple handles are allowed for platforms - youtube, instagram, tiktok, x, threads, other, etc.).
[LIST] Have different fields for each platform that the user can fill with dedicated platform link fields.
[LIST] Follower count for each linked platform (self-reported).
[LIST] Average reach for each linked platform (self-reported).
[LIST] Short bio.
[LIST] Optional portfolio.
[LIST] Optional brand pitch materials, including media kits, rate cards, and presentations.
[LIST] Profile information and uploaded pitch materials are private by default.
[LIST] Members control what they choose to share.
[LIST] Public contestant pages show only approved information with the creator's consent.
[LIST] Manage recurring memberships through secure hosted billing:
[LIST] Update payment cards.
[LIST] View invoices and receipts.
[LIST] Change eligible plans.
[LIST] Cancel or renew subscriptions.
[LIST] View membership status.
[LIST] Resolve payment issues.
[Heading3] B. Dashboard & Private Results
[LIST] Display the current membership level and status.
[LIST] Show:
[LIST] Active competitions.
[LIST] Previously entered competitions.
[LIST] Submitted entries.
[LIST] Upcoming sessions and events.
[LIST] Available opportunities.
[LIST] Announcements.
[LIST] Discounted services.
[LIST] Community/forum access.
[LIST] Notifications.
[LIST] Show whether the member is eligible to vote and provide a clear reason when voting is unavailable.
[LIST] Never display live vote counts or rankings to any creator, including their own.
[LIST] Vote counts remain hidden during voting and verification.
[LIST] After Super Admin verifies and approves results, each contestant can view only their own final verified vote count privately.
[LIST] Final private counts must be released to all contestants simultaneously.
[Heading3] C. Competitions, Submissions & Voting
[LIST] Browse competitions by status:
[LIST] Upcoming.
[LIST] Open.
[LIST] Closed.
[LIST] Results.
[LIST] Enter competitions through video uploads or external video/Reel links.
[LIST] Collect all required entry information.
[LIST] Allow editing or withdrawal before the submission cutoff.
[LIST] Track submission status: draft, pending review, approved, rejected, or withdrawn.
[LIST] Submission forms must record:
[LIST] Acceptance of official competition rules.
[LIST] Permission to display submitted content on public competition pages.
[LIST] Permission for approved marketing and winner-related materials.
[LIST] Exact video upload, processing, and storage workflow remains to be decided.
[LIST] Eligible members with confirmed payment and the required linked social handle can cast one final vote per paid account per competition.
[LIST] Members may vote only for another approved creator.
[LIST] Once submitted, a vote cannot be changed.
[LIST] Display confirmation after successful voting.
[LIST] Explain why voting is unavailable when a member is ineligible.
[LIST] Prevent repeat voting and self-voting, including through another account controlled by the same creator.
Note: A vote represents an eligible paid account, not necessarily a unique individual. A creator cannot vote for their own entry through any account they control. Competition-specific tie-breaking criteria must be published in the competition Rules/FAQ before it opens.
[Heading3] D. Opportunities, Sessions & Services
[LIST] Opportunities page
[LIST] Provide a dedicated Opportunities page for brand campaigns, affiliate programs, collaborations and selective product partnerships.
[LIST] Public visitors see only opportunities marked public. Signed-in creators see public opportunities plus group-targeted and individually assigned opportunities relevant to them.
[LIST] Match targeted opportunities using admin-defined criteria such as niche/category, social platform, follower-count range, location and membership level, or assignment to specific creators.
[LIST] Each listing shows its title, description, opportunity type, eligibility requirements, deadline and an “Apply,” “Inquire” or external application button.
[LIST] Allow creators to search and filter their available listings by type, category and deadline. Show application status where applications are managed within the platform.
[LIST] Restricted opportunities must remain inaccessible to other users, including through direct links.
[LIST] Sessions and registering interest
[LIST] Provide session pages for expert Q&As, workshops and events, showing the topic, speaker, description and confirmed date/time where available.
[LIST] Allow creators to “Register interest” in proposed or upcoming sessions before registration opens. Show confirmation and allow them to withdraw their interest.
[LIST] Registering interest does not reserve a place or automatically register the creator.
[LIST] Notify interested creators when registration opens or confirmed session details become available.
[LIST] Once registration is open, allow eligible creators to register, access joining links and view available recordings.
[LIST] Browse More Ways to Create, including:
[LIST] Discounted shared video editing.
[LIST] Graphic design.
[LIST] Branding.
[LIST] Websites.
[LIST] Media kits.
[LIST] Content repurposing.
[LIST] Discounted tools and member offers.
[LIST] Display available pricing and service inquiry forms.
[LIST] No integrated project-delivery management system is required in Phase 1.
[Heading3] E. Community Forum & Support
[LIST] Private community forum
[LIST] Use Reddit as a functional reference: a forum organized into topic categories, with posts, threaded comments and upvotes/downvotes. A full Reddit clone is not required.
[LIST] Creators can browse categories, search discussions and create posts with a title, body and relevant links.
[LIST] Creators can comment on posts, reply to comments, edit or delete their own content, and upvote/downvote posts and comments. Each member may have only one active upvote or downvote per post or comment. Forum upvotes/downvotes are separate from competition votes.
[LIST] Provide “Newest” and “Top” sorting, with pinned discussions appearing prominently.
[LIST] Allow creators to follow discussions and receive optional notifications for replies.
[LIST] Allow members to report posts or comments. Authorized moderators can review reports, remove content, move posts between categories, pin posts and lock discussions.
[LIST] Display only approved community information, such as display name and avatar. Do not expose email addresses, payment details or private profile materials.
[LIST] Access is restricted to eligible members. No public/downloadable member directory or member contact list is required.
[LIST] Provide a simple Help/Support form covering:
[LIST] Billing problems.
[LIST] Competition entries.
[LIST] Voting issues.
[LIST] Disputes.
[LIST] General inquiries.
[LIST] Members can track support request status or receive email responses.
[Heading3] F. Announcements
[LIST] Provide a dedicated Announcements section for official club news, new competitions, opportunities, sessions, service updates and important platform changes.
[LIST] Each announcement has a title, publication date, full body and optional image or action link.
[LIST] Show announcements to their intended audience: all members, selected plans/groups or competition participants.
[LIST] Display recent announcements on the creator dashboard, with a link to the full announcements archive. Support pinned announcements.
[LIST] Announcements are shared published updates. The notification inbox contains individual messages and alerts.
[LIST] Publishing an announcement may optionally send a notification linking to it and an email copy.
[LIST] Announcements do not require comments or reactions in Phase 1; discussion can take place in a linked forum thread.
[Heading3] G. Notification Center / Internal Inbox
[LIST] Give each creator a private notification center with an unread-count badge (design reference: https://www.awesomescreenshot.com/image/64377447?key=7c6021c8d73ad4c384f2972f9ba812cd).
[LIST] List messages with a subject, short preview, date/time and read/unread status.
[LIST] Clicking a message opens the full email-style message, including its subject, sender (“Creator Club”), body and any relevant action button or link.
[LIST] Mark messages as read when opened; allow creators to mark them unread.
[LIST] Include automated system messages, staff-sent messages, and optional alerts that link to published announcements. Send important notifications to the creator’s registered email as well.
[LIST] This is an inbox for platform messages; member-to-member messaging is not required.
[Heading2] 4. Admin Dashboard: Assigned Operational Modules
Goal: Give operations staff the tools to publish content, manage competitions, and respond to members.
Every action is limited by permissions assigned by Super Admin.
Finance, pricing, global policies, final winner approval, and admin permissions remain exclusive to Super Admin.
[Heading3] A. CMS, Public Content & Communications
[LIST] Manage website pages, public competition and contestant presentation, FAQs, and dashboard content. Announcements are managed separately (see below).
[LIST] Support reusable content types similar to WordPress custom post types.
[LIST] Target content to permitted membership levels or groups.
[LIST] Draft and publish approved:
[LIST] Competition rules.
[LIST] Tie-breaking information.
[LIST] Competition timelines.
[LIST] Winner stories.
[LIST] Manually designed leaderboard images.
[LIST] Changes to locked official rules require Super Admin approval.
[LIST] Authorized admins can compose, preview, schedule and send notification-center messages to individual creators, approved groups or competition participants. Each message must support a subject, full body and optional action button/link, with an option to send an email copy.
[LIST] Authorized admins can manage reusable automated-message templates. Record the sender, recipients, send time and delivery status where available. All actions must follow assigned permissions.
[LIST] Authorized admins can compose, preview, schedule, publish, pin, edit and archive announcements; select the intended audience; and optionally send a linked notification or email. Announcements and notification-center messages must have separate management screens.
[Heading3] B. Competition, Entries & Awards
[LIST] Create and edit competitions with separate:
[LIST] Submission opening dates.
[LIST] Submission closing dates.
[LIST] Submission review periods.
[LIST] Voting opening dates.
[LIST] Voting closing dates.
[LIST] Verification periods.
[LIST] Announcement dates.
[LIST] Manage competition categories, briefs, awards, FAQs/rules, and approved entries.
[LIST] Review creator submissions and required permissions.
[LIST] Approve or reject submissions.
[LIST] Manage public contestant pages.
[LIST] Maintain previous competition archives.
[LIST] Record winner verification stages:
[LIST] Pending.
[LIST] Verified.
[LIST] Disqualified.
[LIST] After approval, track grants/prizes:
[LIST] Pending.
[LIST] Approved.
[LIST] Paid.
[LIST] Record award amount, recipient, and date.
[LIST] Actual payouts occur outside the platform.
[LIST] Draft per-competition tie-breaking rules.
[LIST] Record manual resolution notes where needed.
[LIST] Super Admin approves final rules and results.
[LIST] No random tie-breaking or built-in judging workflow is needed in the MVP.
[Heading3] C. Votes & Member Support
[LIST] Internal live voting dashboard
[LIST] Super Admin and admins with assigned voting-view permissions can access a private live dashboard for each competition.
[LIST] Show total votes received, votes per contestant, an automatically ranked leaderboard, tied positions, unique voting accounts and voting activity over time.
[LIST] Separately display currently counted votes, flagged votes, provisionally excluded votes and invalidated votes. Flagged votes remain counted unless their status requires exclusion.
[LIST] Allow authorized staff to filter by contestant, date/time and vote status, and inspect individual vote records and related eligibility/payment flags. Exports require separate permission.
[LIST] Automatically refresh counts and rankings at least every 30 seconds while voting is open. Display the last-updated time.
[LIST] Label live totals and rankings as provisional until verification and Super Admin certification are complete.
[LIST] Keep this dashboard private to authorized staff. Creators and public visitors must not see live counts or rankings.
[LIST] Staff may flag votes. Invalidation requires separate permission, a recorded reason and an audit trail. Dashboard access does not grant authority to finalize winners or release results.
[LIST] Admins may flag votes for review.
[LIST] Vote invalidation requires a separately assigned permission, a recorded reason, and an audit trail.
[LIST] Review potential bots, duplicate social handles, linked-account self-voting, and disputed payments.
[LIST] Do not reject legitimate multiple paid accounts simply because they share an owner, IP address, or device.
[LIST] Escalate significant disputes to Super Admin.
[LIST] Manage authorized:
[LIST] Member support requests.
[LIST] Opportunity applications.
[LIST] Service inquiries.
[LIST] Community moderation.
[LIST] Member account inquiries.
[LIST] Member-data exports require separate permissions.
[Heading3] D. Opportunities, Events & Services
[LIST] Authorized admins can create, edit, preview, publish, close and archive opportunities, including their details, requirements, deadlines and application method.
[LIST] For each opportunity, select its audience: public, all eligible members, selected groups/categories or specific creators.
[LIST] Build targeted groups using niche/category, social platform, follower-count ranges, location and membership level. Support combined criteria and preview the matching creators before publishing.
[LIST] Use creator profile data for matching. Store follower counts by linked social account, with a last-updated date; automatic social-platform syncing is not required for Phase 1.
[LIST] Manage internal applications and their statuses, and send relevant updates to applicants.
[LIST] Manage proposed and confirmed sessions, interest-registration settings, interested-creator lists, registration links, joining details and recordings. Show separate interest and registration totals.
[LIST] Maintain the shared-services and partner-tools catalog.
[Heading2] 5. Super Admin: Exclusive Controls
Goal: Give the business owner or authorized controller complete oversight of pricing, eligibility, competition integrity, staff permissions, and finances.
[Heading3] A. Admin Permissions, Members & Pricing
[LIST] Create and manage admin accounts.
[LIST] Assign and modify admin permissions.
[LIST] Control member registration, profile privacy, age/geographic restrictions, and platform visibility.
[LIST] Manage membership plans, prices, supported currencies, features, and promotions.
[LIST] Issue:
[LIST] Promotional codes.
[LIST] Invitations.
[LIST] Free/complimentary memberships.
[LIST] Configure expiry dates and applicable access.
[LIST] Complimentary access does not automatically grant voting eligibility.
[LIST] View:
[LIST] Subscriber counts.
[LIST] Monthly recurring revenue (MRR).
[LIST] Source/referral conversions.
[LIST] Revenue.
[LIST] Payments.
[LIST] Cancellations.
[LIST] Failed charges.
[LIST] Refunds.
[LIST] Chargebacks.
[LIST] Export financial reports.
[Heading3] B. Billing, Cancellation & Dispute Policy
Membership Cancellation
[LIST] Cancellation immediately ends new voting rights, even when the paid billing period has not ended.
[LIST] Other prepaid membership access continues until the normal end of the billing period, unless a separate approved restriction applies.
[LIST] Failed or expired payments, refunds, and chargebacks immediately suspend new voting rights.
Refund Policy
[LIST] Proposed policy: No discretionary change-of-mind refunds, particularly once a member has voted.
[LIST] Mandatory consumer rights, billing-error corrections, and payment-provider rules must still be honored.
[LIST] Membership and cancellation terms must be disclosed before purchase.
[LIST] A no-refunds policy cannot prevent a bank or credit card dispute.
Previously Cast Votes
[LIST] Votes legitimately cast before voluntary membership cancellation remain valid.
[LIST] If the payment covering a vote is fully refunded or lost through a chargeback before results are certified, the affected vote is excluded from the final tally after documented review.
[LIST] Historical vote records must be retained.
Pending Payment Disputes
[LIST] Suspend new voting rights.
[LIST] Flag affected previously cast votes.
[LIST] Provisionally exclude disputed votes from result certification until payment evidence is reviewed.
[LIST] Reinstate votes if the dispute is resolved in the member's favor before certification.
[LIST] Super Admin records the outcome.
[LIST] Votes cannot be silently deleted.
Chargebacks After Final Results
[LIST] A later chargeback does not automatically reverse an announced winner.
[LIST] Material fraud must be investigated and recorded.
[LIST] Follow the published correction and appeal procedures.
[LIST] Any exceptional correction requires Super Admin approval.
[Heading3] C. Official Competition & Voting Policies
Eligibility Configuration
Set and publish global and per-competition rules before voting begins, including:
[LIST] Eligible paid membership levels.
[LIST] Minimum account or membership age.
[LIST] Minimum age, checked against the required year of birth in the member profile.
[LIST] Location.
[LIST] Account and payment status.
[LIST] One vote per account per competition.
[LIST] Self-voting prohibition.
[LIST] Submission and voting deadlines.
[LIST] Any waiting period.
Default Launch Rules
[LIST] No membership waiting period after successful payment.
[LIST] Eligible members can join and vote until the published voting deadline.
[LIST] Every paid membership level has equal voting weight.
[LIST] A vote cannot be changed once cast.
Multiple Paid Accounts
[LIST] Different paid accounts with distinct social media handles are allowed.
[LIST] A person may control multiple paid accounts.
[LIST] The same social media handle cannot be linked to more than one membership account.
[LIST] A creator cannot vote for their own entry using another account they control.
[LIST] Multiple accounts are not treated as fraudulent merely because they have the same owner.
Competition Rules
[LIST] Publish all material eligibility, multiple-account, cancellation, vote-review, tie-breaking, and complaint rules in each competition's Rules/FAQ before voting begins.
[LIST] Lock approved voting settings while the competition is active.
[LIST] Exceptional material changes require Super Admin approval, an audit record, notice to affected members, and legal review where necessary.
Tie-Breaking
[LIST] Each competition must have a published, non-random tie-breaking method based on predefined creative judging criteria.
[LIST] Authorized staff document how the tie was resolved.
[LIST] Super Admin approves the final result.
[LIST] No automated judging system is required in Phase 1.
[Heading3] D. Final Results, Grants & Audit
[LIST] Super Admin has full access to every competition’s internal live voting dashboard, leaderboard, contestant totals, vote records, review statuses and voting reports. Super Admin controls which admins may view, review or export this information. Live dashboard rankings do not automatically select or publish winners; final results require verification, certification and explicit Super Admin approval.
Verification
[LIST] Automatically freeze new voting when the voting period closes.
[LIST] Begin a verification period targeted at five calendar days.
[LIST] Extend verification only when a material issue is documented.
[LIST] Allow voting-related complaints until 48 hours after voting closes.
[LIST] Review flagged votes, refunded/disputed payments, and reported irregularities before certification.
[LIST] Publish an explanation if result announcements are delayed.
Appeals
[LIST] Contestants may submit an appeal through the support system within seven calendar days after results are announced.
[LIST] Appeals may challenge the contestant's own outcome.
[LIST] Audit records remain private.
[LIST] An appeal does not automatically suspend publication or entitle the contestant to other voters' private information.
Results & Grants
[LIST] Approve final verified winners and vote totals.
[LIST] Authorize simultaneous release of private final vote counts to all contestants.
[LIST] Approve public winner announcements.
[LIST] Approve official grant/award records.
Audit
Access and export logs covering:
[LIST] Competition rule changes.
[LIST] Vote reviews and invalidations.
[LIST] Membership cancellations and refunds.
[LIST] Admin permission changes.
[LIST] Pricing changes.
[LIST] Result approvals and announcements.
Logs must record who performed an action, what changed, when it occurred, and the reason.
[Heading2] 6. Backend Services & System Safeguards
Goal: Enforce platform rules consistently behind every page, form, payment event, and vote.
Interface restrictions alone are insufficient. Validations, privacy, and audit records must operate server-side.
[Heading3] A. Voting & Eligibility Enforcement
[LIST] Validate eligibility on the server before every vote.
[LIST] Check:
[LIST] Confirmed active payment.
[LIST] Eligible membership level.
[LIST] Claimed and verified distinct social media handle (Verification method to be discussed).
[LIST] Applicable age and geographic restrictions.
[LIST] Any waiting-period requirements.
[LIST] Whether the voting window is open.
[LIST] One-vote-per-account limit (per competition).
[LIST] No self-voting across accounts controlled by the contestant.
[LIST] Allow multiple paid accounts with distinct social handles.
[LIST] Do not block accounts merely because they share a name, device, IP address, or owner.
[LIST] Flag:
[LIST] Duplicate/copied social handles.
[LIST] Coordinated bot activity.
[LIST] Suspicious payment patterns.
[LIST] Linked-account self-voting attempts.
[LIST] Abnormal voting activity.
[LIST] Require documented review of suspicious cases.
[LIST] Never allow admins to fabricate votes or create ballots on behalf of members.
[Heading3] B. Vote Records & Payment Events
[LIST] Store each ballot as an immutable historical record.
[LIST] Support statuses:
[LIST] Valid.
[LIST] Flagged.
[LIST] Provisionally excluded.
[LIST] Invalidated.
[LIST] Reinstated.
[LIST] Record reviewer decisions, reasons, timestamps, linked payment references, and relevant history.
[LIST] Cancellation preserves previously valid votes.
[LIST] Refunded or disputed payments affect vote status according to Section 5B.
[LIST] Never delete original vote records.
[LIST] Billing webhooks must distinguish:
[LIST] Membership cancellation.
[LIST] Failed charges.
[LIST] Voluntary refunds.
[LIST] New payment disputes.
[LIST] Disputes won or lost.
[LIST] Payment reversals.
[LIST] Recalculate certified totals only through controlled review.
[LIST] Preserve original and revised totals and their audit histories.
[Heading3] C. Security, Privacy & Payments
[LIST] Separate public content, private member information, and staff-only live voting data.
[LIST] Authenticate and authorize every protected endpoint.
[LIST] Require multi-factor authentication for admins.
[LIST] Implement rate limiting, abuse controls, backups, and consent/privacy settings.
[LIST] Use hosted payment processing.
[LIST] Never store raw payment card details.
[LIST] Synchronize billing events with the payment provider through webhooks.
[LIST] Enforce opportunity, announcement and forum audience permissions server-side, including direct URLs, search results and notifications. Use admin-defined profile criteria for opportunity matching; an advanced recommendation engine is not required.
[Heading3] D. Tracking & Notifications
[LIST] Track the acquisition journey from public link → registration → payment.
[LIST] Maintain entry and vote timestamps, decisions, status changes, notifications, and audit logs.
[LIST] Automatically create notification-center messages for account/billing updates, submission approvals or rejections, competition deadlines, voting opening/closing, event reminders, approved result releases, grant/prize status updates and forum replies when enabled.
[LIST] Use reusable templates with a subject, full message body and relevant link. Trigger messages from confirmed system events or scheduled reminders.
[LIST] Store each creator’s messages and read/unread status privately. Send email copies for important updates; optional reminders and forum alerts follow notification preferences.
[LIST] Prevent duplicate messages when system events are retried. Log delivery failures and retry failed email deliveries.
[LIST] Result notifications must follow Super Admin approval and release controls. Never include live vote counts, rankings or another contestant’s private final count.
[LIST] Store session interest separately from confirmed registrations, prevent duplicate interest records, and notify interested creators when registration opens.
[Heading2] 7. MVP Scope & Decisions
[Heading3] Included in Phase 1
[LIST] Public competition and contestant pages.
[LIST] Acquisition tracking.
[LIST] Recurring subscriptions.
[LIST] Promotional invitations.
[LIST] Three configurable membership plans.
[LIST] Creator portal.
[LIST] Private final vote counts.
[LIST] Competitions and voting.
[LIST] Grant tracking.
[LIST] Opportunity listings.
[LIST] Events and sessions.
[LIST] Shared creative services catalog.
[LIST] Community forum.
[LIST] Support system.
[LIST] CMS.
[LIST] Email and dashboard notifications.
[LIST] Admin roles and permissions.
[LIST] Internal reports.
[LIST] Super Admin controls.
[LIST] Targeted opportunities.
[LIST] Session interest tracking.
[LIST] Separate announcements section.
[Heading3] Not Required in Phase 1
[LIST] Public live leaderboards.
[LIST] Automated tie-breaking or judging engine.
[LIST] Native livestreaming infrastructure.
[LIST] Creator editing/project management.
[LIST] Brand self-service portal.
[LIST] Public member directory.
[LIST] Advanced recommendations.
[LIST] Dedicated mobile applications.
[LIST] Referral payout/commission program.
[Heading2] MVP Completion Criteria
Public Visitor: Can discover and share an approved competition entry, review competition rules, register, and become a paying member. Acquisition source is tracked.
Creator / Member: Can subscribe, manage their account, enter and promote competitions, vote for eligible contestants, access membership benefits, and eventually see only their own final verified vote count.
Admin: Can perform assigned operational tasks without gaining unauthorized access to financial information, platform policies, or sensitive controls.
Super Admin: Can manage membership pricing, eligibility, competition rules, approvals, financial reports, billing disputes, grants, permissions, and audit records.
Backend: All eligibility, privacy, security, voting, and permission restrictions are consistently enforced by the system.
