async function resolveHandle(handle: string) {
    const res = await fetch(`https://${handle}/.well-known/atproto-did`)
    const did = await res.text()
    assert(typeof did === 'string' && did.startsWith('did:plc:blmecq3hyf34qf5x6dmpikrt'))
    return did
  }