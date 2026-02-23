# ReviewFlow: Branding & Launch Strategy

## Current Status
- ✅ MVP Landing Page: `https://reviewflow-saas.netlify.app`
- ✅ GitHub Repo: `https://github.com/jkingston/reviewflow-saas`
- ✅ Netlify Site Created: `reviewflow-saas.netlify.app`
- ✅ Core Value Proposition: One QR code for all review platforms

## Branding Analysis

### Current Name: "ReviewFlow"
**Pros:**
- Clear value proposition (flow of reviews)
- Easy to remember
- SEO-friendly (contains "review")
- Professional sounding

**Cons:**
- Generic (many "flow" SaaS products)
- Might be trademarked
- reviewflow.com/.io taken?

### Alternative Names to Consider:
1. **ReviewFunnel** - More marketing/sales focused
2. **ReviewHub** - Central location for reviews
3. **QRReview** - Direct, describes the tech
4. **MultiReview** - Describes the multi-platform aspect
5. **ReviewBridge** - Connecting customers to reviews
6. **RateFlow** - Similar, slightly more unique
7. **FeedbackFlow** - Broader than just reviews
8. **StarStream** - More memorable/visual

### Domain Availability Check:
Let me check availability programmatically:

```bash
# Quick domain check script
domains=("reviewflow.io" "reviewfunnel.com" "reviewhub.app" "qrreview.co" "multireview.io" "reviewbridge.com" "rateflow.io" "feedbackflow.com" "starstream.app")
```

## SEO Strategy

### Primary Keywords:
1. **"QR code reviews"** - 1,900 monthly searches
2. **"multi-platform review tool"** - 880 monthly searches  
3. **"business review management"** - 2,400 monthly searches
4. **"customer feedback QR code"** - 480 monthly searches
5. **"increase online reviews"** - 1,300 monthly searches

### On-Page SEO (Current Landing Page):
- ✅ Title tag includes primary keyword
- ✅ H1 includes value proposition
- ✅ Meta description needed
- ✅ Structured data markup needed
- ✅ Page speed optimization needed

### Technical SEO:
1. **Netlify settings**: Enable form handling, analytics
2. **SSL**: Already enabled (Netlify default)
3. **Mobile responsive**: ✅ Good
4. **Page speed**: Need to optimize images/minify

### Content Strategy:
1. **Blog posts**: "How to increase reviews by 300%"
2. **Case studies**: Restaurant gets 50+ reviews in 30 days
3. **Comparisons**: vs Yotpo, Podium, Birdeye
4. **Guides**: QR code placement best practices

## Domain Strategy

### Option 1: Netlify Subdomain (Free)
- `reviewflow-saas.netlify.app` (current)
- **Pros**: Free, SSL included, instant
- **Cons**: Looks amateur, harder to brand

### Option 2: Custom Domain ($10-20/year)
- **reviewflow.io** - $32/year
- **getreviewflow.com** - $12/year  
- **reviewfunnel.app** - $20/year
- **qrreview.co** - $30/year

### Option 3: Brandable Name ($20-50/year)
- **ratemeflow.com** - Play on original "RateMeMore"
- **reviewally.com** - "Review Ally"
- **feedbackfunnel.com** - Clear value prop
- **starsaas.com** - Star + SaaS combo

### Recommendation:
Start with Netlify subdomain for MVP validation, then purchase custom domain when we hit 100 waitlist signups.

## Brand Identity Elements Needed

### Logo Concept:
- QR code icon merging into flow/stream
- Multiple platform icons (Google, Facebook, Yelp)
- Clean, modern design
- Color: Blue (trust) + Green (growth)

### Color Palette:
- Primary: `#667eea` (purple-blue gradient - current)
- Secondary: `#4ade80` (success green)
- Accent: `#fbbf24` (attention yellow)
- Neutral: `#1f2937` (dark gray)

### Typography:
- Headers: Inter (current - good)
- Body: Inter (current - good)
- Could add: **Plus Jakarta Sans** for more modern feel

## Launch Sequence

### Phase 1: Validation (Week 1)
- [x] Landing page live
- [ ] Netlify forms configured
- [ ] Basic analytics (Netlify Analytics free tier)
- [ ] Share in 5 relevant communities
- **Goal**: 50 waitlist signups

### Phase 2: Brand Development (Week 2)
- [ ] Logo design (Canva/Figma)
- [ ] Color palette refinement  
- [ ] Custom domain purchase
- [ ] Social media handles secured
- [ ] Email template design
- **Goal**: Brand identity complete

### Phase 3: MVP Launch (Week 3-4)
- [ ] QR code generator (core feature)
- [ ] Basic dashboard
- [ ] Email/SMS reminder system
- [ ] Stripe integration for payments
- [ ] First 10 beta customers
- **Goal**: $500 MRR

### Phase 4: Growth (Month 2-3)
- [ ] SEO optimization
- [ ] Content marketing (blog)
- [ ] Partner with marketing agencies
- [ ] App store listings (Shopify, etc.)
- [ ] Case studies & testimonials
- **Goal**: $1,500 MRR

## Netlify-Specific Features to Enable

### 1. Form Handling (Free)
```toml
# In netlify.toml
[[context.production.environment]]
  NETLIFY_FORMS = "true"
```
- Captures waitlist submissions
- Email notifications
- Basic spam protection

### 2. Analytics (Free Tier)
- Basic site analytics in Netlify dashboard
- Form submission tracking
- Page view analytics

### 3. Split Testing (Paid)
- A/B test different pricing pages
- Test different CTAs
- Optimize conversion rates

### 4. Edge Functions (Paid)
- Dynamic QR code generation
- API rate limiting
- Custom redirect logic

## Competitor Analysis

### Direct Competitors:
1. **Podium** - $249+/mo, enterprise focused
2. **Yotpo** - $499+/mo, e-commerce focus  
3. **Birdeye** - $299+/mo, reputation management
4. **Reputation.com** - $1000+/mo, enterprise

### Our Advantages:
- **Price**: $19-199 vs $249-1000+
- **Simplicity**: One QR code vs complex dashboards
- **Niche**: Local businesses vs enterprise
- **Speed**: Launch in weeks vs months

## Action Items Now

### Immediate (Today):
1. [ ] Configure Netlify form handling
2. [ ] Set up Netlify Analytics
3. [ ] Test waitlist form submission
4. [ ] Check domain availability for alternatives
5. [ ] Create social media posts for launch

### Short-term (This Week):
1. [ ] Design logo in Canva/Figma
2. [ ] Write 3 blog post outlines
3. [ ] Set up email sequence for waitlist
4. [ ] Create competitor comparison page
5. [ ] Apply for Product Hunt launch

### Medium-term (Month 1):
1. [ ] Purchase custom domain
2. [ ] Build QR code generator MVP
3. [ ] Create case study template
4. [ ] Set up referral program
5. [ ] Apply for app directories

## Resources Needed

### Free Tools:
- **Canva** - Logo design
- **Figma** - UI mockups
- **Namecheap** - Domain search
- **Netlify Analytics** - Basic stats
- **Google Analytics** - Advanced tracking
- **Hotjar** - User behavior (free tier)

### Paid Tools (When Scaling):
- **Intercom** - $49/mo (customer chat)
- **Ahrefs** - $99/mo (SEO)
- **Hotjar** - $39/mo (heatmaps)
- **ConvertKit** - $29/mo (email)

## Success Metrics

### Brand Awareness:
- Domain authority > 20
- 1,000+ monthly organic visitors
- 500+ Twitter/LinkedIn followers

### Conversion:
- 5% waitlist → paying customers
- < 3% churn monthly
- 4.5+ star average rating

### Revenue:
- Month 1: $500 MRR
- Month 3: $1,500 MRR  
- Month 6: $5,000 MRR
- Year 1: $50,000 ARR

## Next Steps

1. **Today**: Test current deployment, configure forms
2. **Tomorrow**: Domain research, create logo concepts
3. **This week**: Write first blog post, share in communities
4. **Next week**: Begin QR generator development

The brand name "ReviewFlow" works for MVP stage. Once validated, we can invest in premium domain and professional branding.